# cookiecutter-python-project

Creation of this package was inspired by [audreyr/cookiecutter-pypackage](https://github.com/audreyr/cookiecutter-pypackage).


## Usage
Important notes: 
<<<<<<< HEAD
- if the [virtualenv](https://virtualenv.pypa.io/en/stable/), ([basic usage](http://docs.python-guide.org/en/latest/dev/virtualenvs/)) is installed skip step 1 below
- some packages may depend on the order listed in requirements.txt or requirements_dev.txt
=======
* if the virtualenv is installed skip step 1 below
* some packages may depend on the order listed in requirements.txt or requirements_dev.txt
>>>>>>> d3a4b1c760240cc48f60295f3ef512b73d60d21e

````
1. $ pip install virtualenv 
2. ~/virtuals$ virtualenv `name_project`
3. $ source ~/virtuals/name_project/bin/activate
4. $ pip install cookiecutter
5. $ cd ~/projects/python/
6. $ cookiecutter git@github.com:ondrej-tucek/cookiecutter-python-project.git
7. fill the questions
8. put into requirements.txt or requirements_dev.txt file packages that you want/need it
9. $ pip install -r requirements_dev.txt
10. ... hard work now! ...
11. $ deactivate
````


## License
 [MIT](/LICENSE)

