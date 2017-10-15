# FlaskApp

Simple application with authentication and CRUD functionality using the Python Flask micro-framework

## Installation 
### Centos 7 with python 3.4

```bash
yum install python34-pip
pip3 install flask-mysqldb
yum install gcc
yum install python34-devel
pip3 install flask-mysqldb
pip3 install WTForms
pip3 install passlib
git clone https://github.com/edib/myflaskapp.git
```
### Creating the database
```sql
create database myflaskapp
use myflaskapp
```
run create table scripts in sql_scripts file.

### Running the app

```bash
python3 app.py
```

