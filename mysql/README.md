# Setup
First, you need to set up 2 things:
## 1. MySQL server 💁‍♂️
Details [here](https://realpython.com/python-mysql/#installing-mysql-server).  
While installing MySQL server, you will need to enter a password for the *root* (admin) account.  
This way you will get the `USER` and `PASSWORD` needed for the `credentials.py` file.
## 2. MySQL connector
Meaning a Python library. Install in shell:
```bash
pip install mysql-connector-python
```
And then check if this runs without errors:
```python
import mysql.connector
```

# Create database
In the notebook `1_create_database.ipynb` you create a database `online_movie_rating`, then create a table `movies` and fill it with data.

After executing this notebook, you can connect to the database e.g. using *MySQL Workbench* (hostname: 127.0.0.1, port: 3306). Then select *schema* and you can execute queries on your database.

# Reference
[Article](https://realpython.com/python-mysql/) about MySQL with Python
