# fastapi-tutorial-userguide
https://fastapi.tiangolo.com/tutorial/

# Pipenv - 
* https://pypi.org/project/pipenv/ 
* https://pipenv.pypa.io/en/latest/
* https://realpython.com/pipenv-guide/
pip3 install pipenv
pipenv shell
pipenv install "fastapi[all]"
pipenv install pytest --dev
pipenv lock

pipenv install --ignore-pipfile 
This tells Pipenv to ignore the Pipfile for installation and use what’s in the Pipfile.lock. Given this Pipfile.lock, Pipenv will create the exact same environment you had when you ran pipenv lock, sub-dependencies and all.

pipenv install --dev
pipenv uninstall numpy
pipenv uninstall --all | all-dev

Lembre-se de alterar o interpreter do python.
Command Pallete > Python select interpreter > Path


uvicorn main:app --reload

