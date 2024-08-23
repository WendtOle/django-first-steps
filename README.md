Django tutorial was used: https://docs.djangoproject.com/en/5.1/intro/tutorial01/

## Setup
Check the path of the python3 installation
```
which python3
```

Create virtual environment
```
`virtualenv -p <path> venv`
```

Activate virtual environment
```
source venv/bin/activate
```

Deactivate later through
```
deactivate
```

Save dependencies currently installed in you venv
```
pip freeze > requirements.txt
```

Install dependencies later again
```
pip install -r requirements.txt
```

Note that the `pip freeze ...` commands should only be run when a venv is activated
