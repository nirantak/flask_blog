# Flask Blog
> *A simple app with authentication and CRUD functionality built using the Python Flask micro-framework*

### Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [Requirements](#requirements)
* [License](#license)

### Installation
Clone the git repository:
```bash
$ git clone https://github.com/nirantak/flask_blog.git && cd flask_blog
```

Install necessary dependencies
```bash
$ pip install -r requirements.txt
```

### Usage
Save MySQL database connection parameters in file **config.py** as:
```python
HOST     = "mysql_hostname_here"  # default='localhost'
USER     = "mysql_username_here"  # default='root'
PASSWORD = "mysql_password_here"
DB       = "flaskblog"
```

```bash
$ python app.py
```

### Requirements
1. [Python](https://python.org)
2. [MySQL](https://www.apachefriends.org/download.html)

### License
This code has been released under [The Unlicense](LICENSE).
