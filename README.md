# cookiecutter-python-project

Creating of this package was inspired by [audreyr/cookiecutter-pypackage](https://github.com/audreyr/cookiecutter-pypackage).


# Usage
1. $ pip install [virtualenv](https://virtualenv.pypa.io/en/stable/), [basic useage](http://docs.python-guide.org/en/latest/dev/virtualenvs/)
2. ~/virtuals$ virtualenv `name_project
3. $ source ~/virtuals/`name_project`/bin/activate
4. $ pip install cookiecutter
5. $ cd ~/projects/python/
6. $ cookiecutter git@github.com:ondrej-tucek/cookiecutter-python-project.git
7. fill the questions
8. put into requirements.txt file a packages that you want/need it
9. $ pip install -r requirements_dev.txt
10. ... hard work now! ...
11. deactivate

Important notes: 
- some packages may depend on the order listed in requirements.txt or requirements_dev.txt


# License
 [MIT](/LICENSE)

