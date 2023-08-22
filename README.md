# flask-ds
Data structures with Flask by building a Flask API with Python

## Changes made: 


## Issues: 

```
Fix no user tbl issue by using within server.py underneath config-> app.app_context().push() 

then:
from server import db
>>> db.create_all()
>>> exit()
```


## Resources used:

original repo -> https://github.com/selikapro/FlaskDS

https://www.youtube.com/watch?v=74NW-84BqbA&pp=ygUUZmxhc2sgZGF0YSBzdHJ1Y3R1cmU%3D

https://flask.palletsprojects.com/en/2.3.x/installation/#install-flask

https://docs.sqlalchemy.org/en/20/intro.html#installation

https://pypi.org/project/Flask-SQLAlchemy/

https://www.toptal.com/developers/gitignore/

https://sqlitebrowser.org/dl/

https://www.postman.com/downloads/

https://stackoverflow.com/questions/44941757/sqlalchemy-exc-operationalerror-sqlite3-operationalerror-no-such-table

https://www.programcreek.com/python/example/81989/app.db.drop_all

https://stackoverflow.com/questions/64233968/sqlalchemy-no-such-table-user

https://flask-sqlalchemy.palletsprojects.com/en/3.0.x/quickstart/

https://stackoverflow.com/questions/20744277/sqlalchemy-create-all-does-not-create-tables

https://www.reddit.com/r/flask/comments/ykm1w4/dbcreate_all_not_working/

https://python-forum.io/thread-39328.html

https://stackoverflow.com/questions/31444036/runtimeerror-working-outside-of-application-context