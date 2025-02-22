# observer-hive: frontend
> Track your projects in real-time

This module is the client side server process of the observer-hive. It allows you to process events received
from webservices such as Gitlab, Jenkins and Sonarqube. If you are interested in the full project you should
take a look at its counterpart: the [conductor server](https://iteragit.iteratec.de/observer-hive/scab-oberserver-hive).

[![Build Status](https://www.travis-ci.org/Afsharov/observer-frontend.svg?branch=master)](https://travis-ci.org/Afsharov/observer-frontend) [![codecov](https://codecov.io/gh/Afsharov/observer-frontend/branch/master/graph/badge.svg?token=LC3BB7EZFA)](https://codecov.io/gh/Afsharov/observer-frontend) 


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

This application is meant to run on a RaspberryPi. What should be installed:

* [Raspbian](https://www.raspberrypi.org/downloads/raspbian/) - the operating system on the RaspberryPi
* [Python 3.x](https://www.python.org) - usually comes with Raspbian
* [pip]() - package management system which comes with the newer versions of Python

### Installing

### With pip

We recommend creating a virtual environment with `virtualenv` to run the app. If have never used a 
virtual environment or seek a little insight on why to use it have a look at this short 
[tutorial](http://www.pythonforbeginners.com/basics/how-to-use-python-virtualenv/).
Once you have the package on your computer you simply install the package by using `pip` :

```
pip3 install .
```

Of course, depending on your system and version of `Python` you might have to substitute the command 
`pip3` for `pip`.

## Running the tests

`pytest` has been setup as the test runner of this package. You can run the tests with the following command:

```
python3 setup.py test
```

## Deployment

We have written an extensive manual on the scab-observer-hive project where you can find instructions
on how to [deploy the client server on your RaspberryPi](). 

## Documentation

The docs of the modules have been generated by `Sphinx`. In the docs > _build > html directory you will find the
`index.html` which is the main page of the documentation. If you make changes to the docs and want to re-generate
the html files then run from within the docs folder:

```
make clean
make html
```

For more information on `Sphinx` and how to expand the docs see 
[its official documentation](http://www.sphinx-doc.org/en/master/).

## Built With

* [Flask](http://flask.pocoo.org/) - lightweight WSGI web application framework

## Versioning

We use [GitHub](https://github.com/) for versioning. For the versions available, see the [tags on this repository](https://github.com/Afsharov/observer-frontend/tags). 

## Authors

* **Gerd Neugebauer** - [ge-ne](https://github.com/ge-ne) - *Idea*
* **Masud Afschar** - [Afsharov](https://github.com/Afsharov) - *Initial work*

See also the list of [contributors](https://github.com/Afsharov/observer-frontend/graphs/contributors) who participated in this project.

## License

This project is licensed under the BSD 3-Clause License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* Many thanks to **Chau** - [Chau362](https://github.com/Chau362) - for his constant help.