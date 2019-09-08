Intro to Python Workshop, San Diego, 2014
==========================================

Brought to you by San Diego Python, San Diego PyLadies, Inland Empire Python, 
Inland Empire PyLadies.

This repo is adapted from the geekgirl repo, which was for the San Diego PyLadies 
workshop at the Geek Girl Tech Conference on Saturday June 21, 2014.

Run it in your browser:

.. image:: https://mybinder.org/badge_logo.svg
 :target: https://mybinder.org/v2/gh/pythonsd/intro-to-python/master

Instructions For Students
=============================

Before coming to the workshop, do the pre-workshop setup: `part-0.ipynb`_

Workshop Agenda and Files
-------------------------

Students can follow along with the slides and speaker notes. This is helpful 
in case anyone falls behind and misses something.

9:30-12:30 Morning
~~~~~~~~~~~~~~~~~~~

Welcome and Intros

* Finish setup if you haven't yet: `part-0.ipynb`_

20 Cool Things You Can Do With Python, Part A

* Slides: `20-things-part-a.pdf`_

Part 1: Numbers, strings, variables, booleans, "if statements"

* REPL demo examples: `part-1.ipynb`_

Part 2: Lists and loops

* REPL demo examples: `part-2.ipynb`_

12:30-1:15pm Lunch break
~~~~~~~~~~~~~~~~~~~~~~~~~

Eat and meet other students.

1:15-4pm Afternoon
~~~~~~~~~~~~~~~~~~~

20 Cool Things You Can Do With Python, Part B

* Slides: `20-things-part-b.pdf`_

Functions and modules

* Slides: `part-3.pdf`_
* Code examples: `part3/`_

List comprehensions, dictionaries, and tuples

* REPL demo examples: `part-4.ipynb`_

Conclusion: stdlib, PyPI, next steps

* Slides: `conclusion.pdf`_

* `Survey`_

Instructions For Instructors
=============================

Giving the Talk
---------------

Before giving the talk, IPython Notebook must be installed:

.. code-block:: bash

    $ pip install 'ipython[notebook]'

How to run an IPython Notebook:

.. code-block:: bash

    $ ipython notebook part-1.ipynb

You can view each of the files online using `nbviewer`_.

At the workshop we gave the talk like this:

* We opened a Python shell on the projector monitor and an IPython notebook on the laptop monitor
* One person read the notebook and typed into the Python shell
* Another person stood in front of the audience and explained each step
* Questions were answered ad-hoc, occasionally by Googling answers or typing at the terminal


Copying
-------

You can give this talk too!

This work is licensed under a `Creative Commons Attribution 4.0 International License`_. See LICENSE_ file for more details.


.. _nbviewer: http://nbviewer.ipython.org/
.. _part-0.ipynb: http://nbviewer.ipython.org/github/pythonsd/intro-to-python/blob/master/part-0.ipynb
.. _20-things-part-a.pdf: https://github.com/pythonsd/intro-to-python/tree/master/slides/20-things-part-a.pdf
.. _part-1.ipynb: http://nbviewer.ipython.org/github/pythonsd/intro-to-python/blob/master/part-1.ipynb
.. _part-2.ipynb: http://nbviewer.ipython.org/github/pythonsd/intro-to-python/blob/master/part-2.ipynb
.. _20-things-part-b.pdf: https://github.com/pythonsd/intro-to-python/tree/master/slides/20-things-part-b.pdf
.. _part-3.pdf: https://github.com/pythonsd/intro-to-python/tree/master/slides/part-3.pdf
.. _`part3/`: https://github.com/pythonsd/intro-to-python/tree/master/part3
.. _part-4.ipynb: http://nbviewer.ipython.org/github/pythonsd/intro-to-python/blob/master/part-4.ipynb
.. _conclusion.pdf: https://github.com/pythonsd/intro-to-python/tree/master/slides/conclusion.pdf
.. _Survey: https://www.surveymonkey.com/s/8KX9GGQ
.. _Creative Commons Attribution 4.0 International License: http://creativecommons.org/licenses/by/4.0/
.. _LICENSE: LICENSE
