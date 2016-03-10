# The Python Way [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/alephmelo/python-way#fork-destination-box)

This document is intended to help you on your way to be the so called Full Stack Python Developer. It will include a curated list of articles, talks, tutorials and others great materials out there.

![Pymap](../master/assets/pymap.png?raw=true)

# Table of Contents

- [Beginning](#beginning)
  - [Command Line](#command-line)
  - [Variables](#variables)
  - [Functions](#functions)
  - [Classes](#classes)
  - [Exceptions](#exceptions)
  - [Packages/Modules](#modules)
- [Advanced](#advanced)
	- [List Comprehensions](#list-comprehensions)
	- [Decorators](#decorators)
	- [Context Managers](#context-managers)
	- [Class Decorators](#class-decorators)
	- [Meta Classes](#meta-classes)
- [Optimization](#optimization)
	- [Cython](#cython)
	- [PyPy](#pypy)
	- [Numba](#numba)
- [Concurrency](#concurrency)
	- [Threading](#threading)
	- [Multiprocessing](#multiprocessing)
	- [Async](#async)
		- [Tulip](#tulip)
		- [Gevent](#gevent)
		- [Twisted](#twisted)
- [Testing](#testing)
	- [Unittest](#unittest)
	- [Tox](#tox)
	- [PyTest](#pytest)
	- [CoveragePy](#coveragepy)
- [Data Science](#data-science)
	- [Natural Language Toolkit](#natural-language-toolkit)
	- [Redshift](#redshift)
	- [CSV](#csv)
	- [Pandas](#pandas)
	- [PyLearn2](#pylearn2)
	- [Sckit-Learn](#sckit-learn)
	- [PyMC](#pymc)
	- [Theano](#theano)
	- [Statsmodels](#statsmodels)
- [Web](#web)
	- [HTTP](#http)
	- [Django](#django)
	- [Pyramid](#pyramid)
	- [Flask](#flask)
	- [Bottle](#bottle)
	- [Web2Py](#web2py)
- [Database](#database)
	- [DBAPI](#dbapi)
	- [Django ORM](#django-orm)
	- [SQLAlchemy](#sqlalchemy)
	- [Alembic](#alembic)
- [Data Visualization](#data-visualization)
	- [Bokeh](#bokeh)
	- [Matplot Lib](#matplot-lib)
	- [Seaborn](#seaborn)
	- [Mpld3](#mpld3)
- [Scientific](#scientific)
	- [NumPy](#numpy)
	- [SciPy](#scipy)
- [Packaging](#packaging)
	- [SetupPy](#setuppy)
	- [Wheel](#wheel)
	- [PIP](#pip)
	- [Pypi](#pypi)
- [Documentation](#documentation)
	- [Restructured Text](#restructured-text)
	- [Sphinx](#sphinx)
	- [Readthedocs](#readthedocs)
- [GUI](#gui)
	- [Pygame](#pygame)
	- [Kivy](#kivy)
	- [PySide](#pyside)
	- [PyQT](#pyqt)
- [Community](#community)
  
## Beginning

#### Command Line
- [Documentation](https://docs.python.org/3.5/using/cmdline.html)
- [Command Line Arguments](http://www.tutorialspoint.com/python/python_command_line_arguments.htm)
- [Command line basics](http://alephmelo.github.io/command-line-basics/)

#### Variables
- [Variables and Types](http://www.learnpython.org/en/Variables_and_Types)
- [Python Variable Types](http://www.tutorialspoint.com/python/python_variable_types.htm)
- [Python Basics: Dictionaries](https://www.youtube.com/watch?v=ZX1CVvZLE6c)
- [The Idiomatic Way to Merge Dictionaries in Python](https://treyhunner.com/2016/02/how-to-merge-dictionaries-in-python/)

#### Functions
- [Learn Python The Hard Way](http://learnpythonthehardway.org/book/ex21.html)
- [Functions in Python](http://zetcode.com/lang/python/functions/)
- [Functions Codecademy](https://www.codecademy.com/courses/python-beginner-c7VZg/0/1?curriculum_id=4f89dab3d788890003000096)
- [Automate Boring Stuff with Python](https://automatetheboringstuff.com/chapter3/)

#### Classes
- [Learning To Speak Object Oriented](http://learnpythonthehardway.org/book/ex41.html)
- [Classes and Objects](http://www.learnpython.org/en/Classes_and_Objects)
- [Python Object Oriented](http://www.tutorialspoint.com/python/python_classes_objects.htm)
- [Improve Your Python: Python Classes and Object Oriented Programming](https://www.jeffknupp.com/blog/2014/06/18/improve-your-python-python-classes-and-object-oriented-programming/)
- [The origins of the class Meta idiom in python](http://mapleoin.github.io/perma/python-class-meta)

#### Exceptions
- [Python Exceptions Handling](http://www.tutorialspoint.com/python/python_exceptions.htm)
- [Errors and Exceptions](https://docs.python.org/3.5/tutorial/errors.html)
- [Handling Exceptions](https://wiki.python.org/moin/HandlingExceptions)
- [Python Error: Trey, Except and Exception Handling](http://www.dotnetperls.com/error-python)

#### Modules
- [Modules Every Python Developer Should Know](https://www.reddit.com/r/Python/comments/3yg2u4/modules_every_python_developer_should_know/)
- [Python 101: All about imports](http://www.blog.pythonlibrary.org/2016/03/01/python-101-all-about-imports)

## Advanced

#### List Comprehensions
- [List Comprehensions Basics](http://community.pythonhackers.com/t/list-comprehensions/579)
- [List Comprehensions Explained](http://python-3-patterns-idioms-test.readthedocs.org/en/latest/Comprehensions.html)
- [List Comprehension](http://www.python-course.eu/list_comprehension.php)
- [Yet Another List Comprehension Article](http://www.bogotobogo.com/python/python_list_comprehension.php)

#### Decorators
- [Decorators Part I](http://community.pythonhackers.com/t/decorators-part-1/582)
- [Decorators Part II](http://community.pythonhackers.com/t/decorators-part-ii/583)
- [A Primer on Python Decorators](https://realpython.com/blog/python/primer-on-python-decorators/)
- [Improve Your Python: Decorators Explained](http://www.jeffknupp.com/blog/2013/11/29/improve-your-python-decorators-explained/)

#### Context Managers
- [Introduction to Context Managers in Python](http://eigenhombre.com/2013/04/20/introduction-to-context-managers/)
- [Context Managers 101](http://book.pythontips.com/en/latest/context_managers.html)
- [Context Lib](https://pymotw.com/2/contextlib/)

#### Class Decorators
- [Decorator Classes](http://book.pythontips.com/en/latest/decorators.html#decorator-classes)
- [Writing a Class Decorator in Python](https://andrefsp.wordpress.com/2012/08/23/writing-a-class-decorator-in-python/)

#### Meta Classes
- [Python 3 OOP - Metaclasses](http://lgiordani.com/blog/2014/09/01/python-3-oop-part-5-metaclasses/#.Vpqwj1MrKcw)
- [Decorators and Metaclasses](http://lgiordani.com/blog/2014/10/14/decorators-and-metaclasses/#.Vpqwc1MrKcw)

## Optimization
- [Python: An Intro to caching](http://www.blog.pythonlibrary.org/2016/02/25/python-an-intro-to-caching/)

#### Cython
- [Basic Tutorial](http://docs.cython.org/src/tutorial/cython_tutorial.html)

#### PyPy
- [What is PyPy?](http://doc.pypy.org/en/latest/introduction.html)

#### Numba
- [First Steps with Numba](http://numba.pydata.org/numba-doc/0.12.2/tutorial_firststeps.html)
- [Python Performance and Introduction to Numba - PyData Conf 2015](https://speakerdeck.com/teoliphant/performance-python-and-introduction-to-numba)

## Concurrency

#### Threading
- [Python Multithreading: Advanced Python Concepts](http://www.techbeamers.com/python-multithreading-concepts/)

#### Multiprocessing

#### Async

##### Tulip

##### Gevent

##### Twisted

## Testing
- [Testing Your Code](http://docs.python-guide.org/en/latest/writing/tests/)

#### Unittest
- [An Introduction to Mocking in Python](http://www.toptal.com/python/an-introduction-to-mocking-in-python)

#### Tox

#### PyTest

#### CoveragePy

## Data Science
- [5 important Python Data Science advancements of 2015](https://medium.com/@elgehelge/the-5-most-important-python-data-science-advancements-of-2015-a136482da89b#.tpxagwdl4)
- [100 Data Science in Python Interview Questions and Answers](https://www.dezyre.com/article/100-data-science-in-python-interview-questions-and-answers/188)
- [Time Series Analysis using iPython](http://bicorner.com/2015/11/16/time-series-analysis-using-ipython/)
- [A Complete Tutorial to Learn Data Science with Python from Scratch](http://www.analyticsvidhya.com/blog/2016/01/complete-tutorial-learn-data-science-python-scratch-2/)
- [Python NLTK Tools List for Natural Language Processing (NLP)](http://www.datasciencecentral.com/profiles/blogs/python-nlp-tools)
- [The Definitive Guide to Natural Language Processing](https://blog.monkeylearn.com/the-definitive-guide-to-natural-language-processing/)
- [Primeiros passos com Data Science](http://www.lerrua.com/blog/2016/03/08/primeiros-passos-com-data-science/)

#### Natural Language Toolkit
- [Analyzing Text with the Natural Language Toolkit](http://www.nltk.org/book/)
- [Dive Into NLTK, Part I: Getting Started with NLTK](http://textminingonline.com/dive-into-nltk-part-i-getting-started-with-nltk)
- [NLTK in 20 Minutes](http://www.slideshare.net/japerk/nltk-in-20-minutes)

#### Redshift
- [Introduction to Python UDFs in Amazon Redshift](https://blogs.aws.amazon.com/bigdata/post/Tx1IHV1G67CY53T/Introduction-to-Python-UDFs-in-Amazon-Redshift)
- [Python Language Support for UDFs](http://docs.aws.amazon.com/redshift/latest/dg/udf-python-language-support.html)
- [Redshift User Defined Functions in Python](https://www.periscopedata.com/blog/redshift-user-defined-functions-python.html)

#### CSV

#### Pandas

#### PyLearn2

#### Sckit-Learn
- [Machine Learning in Python](http://www.scipy-lectures.org/advanced/scikit-learn/index.html)

#### PyMC

#### Theano
- [Tutorial](http://deeplearning.net/software/theano/tutorial/)

#### Statsmodels

## Web
- [Django vs Flask vs Pyramid: Choosing a Python Web Framework](https://www.airpair.com/python/posts/django-flask-pyramid)
- [Python, Ruby, and Golang: A Web Service Application Comparison](https://realpython.com/blog/python/python-ruby-and-golang-a-web-Service-application-comparison/)
- [iOS and Web Browser Video Calls with Python and Swift](https://www.twilio.com/blog/2016/02/ios-and-web-browser-video-calls-with-python-and-swift-2.html)

#### HTTP
- [Create a Simple Python Web Scraper to Get Pricing Data](http://robertwdempsey.com/simple-python-web-scraper-get-pricing-data/)
- [Scrapy Tips from the Pros: Part 1](https://blog.scrapinghub.com/2016/01/19/scrapy-tips-from-the-pros-part-1/)

#### Django
- [Web Development with Python and Django (2015)](https://speakerdeck.com/mpirnat/web-development-with-python-and-django-2015)
- [Django Development with Docker Compose and Machine](https://realpython.com/blog/python/django-development-with-docker-compose-and-machine/)
- [Building a better user experience for deploying Python web applications](http://blog.dscpl.com.au/2016/02/building-better-user-experience-for.html)

#### Pyramid

#### Flask
- [Flask by Example - Project](https://realpython.com/blog/python/flask-by-example-part-1-project-setup/)
- [Build an API under 30 lines of code with Python and Flask](https://impythonist.wordpress.com/2015/07/12/build-an-api-under-30-lines-of-code-with-python-and-flask/)
- [Building a Database driven RESTFUL API in Python 3 with Flask](http://techarena51.com/index.php/buidling-a-database-driven-restful-json-api-in-python-3-with-flask-flask-restful-and-sqlalchemy/)
- [The Ultimate Flask Front-End](https://realpython.com/blog/python/the-ultimate-flask-front-end/)
- [A beginner's guide to building a simple database-backed Flask website on PythonAnywhere](http://blog.pythonanywhere.com/121/)
- [Episode #48: Building Flask-based Web Apps](https://talkpython.fm/episodes/show/48/building-flask-based-web-apps)

#### Bottle

#### Web2Py

## Database

#### DBAPI

#### Django ORM

#### SQLAlchemy

#### Alembic

## Data Visualization
- [Cheat sheet: Data Visualisation in Python](http://www.analyticsvidhya.com/blog/2015/06/data-visualization-in-python-cheat-sheet/)

#### Bokeh

#### Matplot Lib

#### Seaborn

#### Mpld3

## Scientific

#### NumPy

#### SciPy

## Packaging

#### SetupPy

#### Wheel

#### PIP

#### Pypi

## Documentation

#### Restructured Text

#### Sphinx

#### Readthedocs

## GUI

#### Pygame
- [PyGame - a Primer](https://realpython.com/blog/python/pygame-a-primer/)
- [Space Shooter Project](https://github.com/prodicus/spaceShooter)

#### Kivy

#### PySide

#### PyQT
-  [Create a GUI Application Using Qt and Python in Minutes: Example Web Browser](http://www.digitalpeer.com/blog/create-a-gui-application-using-qt-and-python-in-minutes-example-web-browser)

## Community
- [Beginner-friendly Python Open Source Projects](https://gist.github.com/ossanna16/330f45fe37d6150138bd)
- [Best Python Resources](http://www.fullstackpython.com/best-python-resources.html?utm_content=bufferc1b6f&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)
- [PEP about diversity in pythonist communities](https://github.com/yamila-moreno/pepa)
- [Do Your Slides At The Last Minute: 8 Steps To Writing Your Con Talk](https://emptysqua.re/blog/how-i-write-a-conference-talk/)
- [The Remote Manifesto](https://about.gitlab.com/2015/04/08/the-remote-manifesto/)
- [Entry Level Quiz for Python Developers](http://www.techbeamers.com/entry-level-quiz-for-python-developers/)
- [PEP 8 — the Style Guide for Python Code](http://pep8.org/)
