- [Venv Tutorial](https://docs.python.org/3/tutorial/venv.html)
# Venv with Github #

Typically the steps you always take are:
```markdown
git clone <repo>
cd <repo>
pip install virtualenv (if you don't already have virtualenv installed)
virtualenv venv to create your new environment (called 'venv' here)
source venv/bin/activate to enter the virtual environment
pip install -r requirements.txt to install the requirements in the current environment or alternatively
pip install -r /path/to/requirements.txt
```

And to create a requirements.txt folder using your venv:
```markdown
pip3 freeze > requirements.txt
```
