# This repository serves as a test repository for connecting PostGreSQL to Python, using commands for PostGreSQL from the Python command line.

### Steps finished:
1. [Connecting to a PostgreSQL database server](https://www.postgresqltutorial.com/postgresql-python/connect/)
- Activating a python virtual environment using `venv/scripts/activate`)
- Install requirements text file using `pip install -r requirements.txt`)
2. [Create Tables](https://www.postgresqltutorial.com/postgresql-python/create-tables/)
- Load commands as strings in the create_tables.py file
- Connection cursor executes the commands with `cur.execute(command)`
3. [Insert Data Into a Table](https://www.postgresqltutorial.com/postgresql-python/insert/)
- Command is seen as string stored in sql variable in insert.py file