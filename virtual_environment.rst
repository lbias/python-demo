.. _virtual_environment:

*******************
Virtual Environment
*******************


.. _install_python3:

Step1, Install python3
======================

* Method 1 (recommendation)

Go to `Python Official Website<https://www.python.org/downloads/>`, download and 
install a specific release.

* Method 2 

Use HomeBrew, `$ brew install python3` 

Make sure Python3 has been installed successfully, $ python3 -V

.. image:: _static/1.png

.. _install_virtualenvwrapper:

Step2, Install package virtualenvwrapper
========================================

#. `$ pip3 install virtualenvwrapper`, `http://virtualenvwrapper.readthedocs.io/en/latest/`

.. image:: _static/2.png

#. check the package location, `$ pip3 show -f virtualenvwrapper`

.. image:: _static/3.png

#. setup the path for shell zsh

.. image:: _static/4.png

#. create a new environment, `$ mkvirtualenv env1`

.. image:: _static/5.png


.. image:: _static/6.png

#. show the existing environment, `$ workon`, or `$ lsvirtualenv`

.. image:: _static/7.png


.. image:: _static/17.png

#. use an existing environment, or switch between environments, `$ workon env1`

.. image:: _static/8.png


.. image:: _static/10.png


.. image:: _static/11.png

#. You must use deactivate before removing the current environment, `$ deactivate`

.. image:: _static/9.png

#. remove an environment, `$ rmvirtualenv env1`

.. image:: _static/12.png
