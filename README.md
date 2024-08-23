- go to directory
- run `which python3` 
- will output path to python3 installation
- use path in following command `virtualenv -p <path> venv
- active venv with `source venv/bin/activate`

- to save dependencies currently installed in you venv
- run `pip freeze > requirements.txt`

- in install dependencies later again
- run `pip install -r requirements.txt`

- note that the `pip freeze ...` commands should only be run when a venv is activated
