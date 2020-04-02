<h1 align="center">Flask-RESTX as Python Package Cookie</div>

<div align="center">
  <img src="https://i.pinimg.com/originals/ac/a4/95/aca4951fa1d8d6da682821bc467ea6ce.png" alt="cookie-monster" border="0" height="300px">
</div>

## Features

This cookie provides the following features:

* A [Flask-RESTX](https://github.com/python-restx/flask-restx) API properly defined skeleton
* An [argparse](https://docs.python.org/3/library/argparse.html) client which defines the entry point of the API
* [Pytest](https://docs.pytest.org/en/latest/) unit tests
* [Swagger.io](https://swagger.io/) automatic API reference documentation
* and much more that will be progressively included...

## Installation

Firstly, you will need to install [cookiecutter]() using pip from a Python3.6 version or higher since this cookie recipe just works on Python3.6+; use the following command:

``pip install cookiecutter``

So as to create your own cookie from this recipe you will need to clone this repository into your machine using the following command:

``git clone https://github.com/alvarobartt/restx-cookie``

Once it is properly cloned, from the working directory, you will need to pass the cloned cookie as an argument to the cookiecutter entry point as it follows:

``cookiecutter /path/to/restx-cookie``

This command will launch the cookiecutter prompt into your terminal, which will ask you some configuration options as specified in the cookie recipe for you to select the most suitable ones according to your needs.

So to bake this cookie, the cookiecutter prompt will ask you to select the following ingredients (configuration) in case you want to name your cookie (project) `awesome_cookie` for example:

```
author [Alvaro Bartolome del Canto]: Cookie Monster
email [alvarobartt@example.com]: cookiemonster@sesamestreet.com
github_username [alvarobartt]: cookie-monster       
project_name [Flask Restx API]: awesome-cookie
project_description [This project is a sample Python Flask Restx API]: This is an awesome cookie!   
repo_name [awesome_cookie]: awesome_cookie
package_name [awesome_cookie]: awesome_cookie
pypi_username [cookie-monster]: cookie-monster
version [0.1]: 1
flask_limiter [yes]: yes
flask_cache [yes]: yes
flask_cors [yes]: yes
```

Once this process is finished, automatically a directory named as specified in `repo_name` will be created containing the following files and directories:

``awesome_cookie/  MANIFEST.in  README.md  requirements.txt  setup.cfg  setup.py  tests/``

Congratulations! You already baked your own restx-cookie!

## Usage

Once the cookie is completely baked, you can take it off the oven! So on, from the `repo_name` previously created directory, so as to install the Flask RESTX API (since it is a Python package) you will need to run on of the following commands: `pip install .` or `python setup.py install`, which will install not just the package but all its dependencies.

Once the newly created cookie is installed, just paste its entry point on the command line as it follows:

`awesome_cookie`

which will launch the Flask RESTX API in your public API (0.0.0.0) in the port 5000 using the current version (which by deafult is the v1 version), so the complete address of the API is: `http://0.0.0.0:5000/v1`. In that address you will find the Swagger.io documentation automatically generated so as to know which endpoints are available, which data models are integrated, which is the input/output structure, etc.

Now you are completely free to eat your cookie!

## Cookie recipe created by...

<table>
  <tr>
    <td align="center"><a href="https://github.com/alvarobartt"><img src="https://avatars3.githubusercontent.com/u/36760800?s=460&v=4" width="100px;" alt=""/><br/><sub><b>Álvaro Bartolomé</b></sub></a><br/><a title="Code">💻</a> <a title="Documentation">📖</a><a title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/gabrielmbmb"><img src="https://avatars2.githubusercontent.com/u/29572918?s=460&v=4" width="100px;" alt=""/><br/><sub><b>Gabriel Martín</b></sub></a><br/><a title="Code">💻</a><a title="Ideas, Planning, & Feedback">🤔</a></td>
  </tr>
</table>

## Want more cookies?

You can find a curated collection of self made cookies at [cookie-jar](https://github.com/alvarobartt/cookie-jar)

## You don't like this cookie? You don't like the chef/chefs?

If you don't like neither the cookie neither the chef (or chefs), to each his own... here we do not judge you (just a little), here you have a list of some similar cookie recipes you may like:

- []()

## You want to become a chef too?

Maybe after seeing this cookie recipe your inner chef spirit came out and you decided to become a chef, well, we already thought this may happen, so here you have a list of useful links on your way to become a real chef (well, not a real one just a programming chef somehow):

- []()
