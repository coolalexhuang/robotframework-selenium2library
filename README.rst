Selenium 2 (WebDriver) library for Robot Framework
==================================================

.. image:: https://api.travis-ci.org/rtomac/robotframework-selenium2library.png


Introduction
------------

Selenium2Library is a web testing library for Robot Framework
that leverages the `Selenium 2 (WebDriver)`_ libraries from the
Selenium_ project.

It is modeled after (and forked from) the SeleniumLibrary_ library, 
but re-implemented to use Selenium 2 and WebDriver technologies.

- More information about this library can be found on the Wiki_ and in the `Keyword Documentation`_.
- Installation information is found in the `INSTALL.rst` file.
- Developer information is found in `BUILD.rst` file.


Installation
------------

You can install Selenium2Library using pip, with the following command

    pip install robotframework-selenium2library


Directory Layout
----------------

demo/
    A simple demonstration, with an application running on localhost

doc/
    Keyword documentation

src/
    Python source code


Usage
-----

To write tests with Robot Framework and Selenium2Library, 
Selenium2Library must be imported into your Robot test suite.
See `Robot Framework User Guide`_ for more information.


Running the Demo
----------------

The demo directory contains an easily executable demo for Robot Framework
using Selenium2Library. To run the demo, run::

    python demo/rundemo.py

E.g.::

	python demo/rundemo.py demo/login_tests
	
Getting Help
------------
The `user group for Robot Framework`_ is the best place to get help. Consider including in the post:

- Full description of what you are trying to do and expected outcome
- Version number of Selenium2Library, Robot Framework, and Selenium
- Traceback or other debug output containing error information

.. _Selenium: http://selenium.openqa.org
.. _Selenium 2 (WebDriver): http://seleniumhq.org/docs/03_webdriver.html
.. _SeleniumLibrary: http://code.google.com/p/robotframework-seleniumlibrary/
.. _Wiki: https://github.com/rtomac/robotframework-selenium2library/wiki
.. _Keyword Documentation: http://rtomac.github.com/robotframework-selenium2library/doc/Selenium2Library.html
.. _Robot Framework User Guide: http://code.google.com/p/robotframework/wiki/UserGuide
.. _user group for Robot Framework: http://groups.google.com/group/robotframework-users


Add by CoolAlex on 07-Aug-2013
Created on 7-Aug-2013 by Alex Huang
Robot framework and selenium installation guide.
1. Install python-2.7.4.msi to C:\python27, refer to: http://www.python.org/download/releases/2.7.4/
2. Add C:\Python27, C:\Python27\Scripts to system PATH
3. Install wxPython2.8-win32-unicode-2.8.12.1-py27.exe, refer to: http://sourceforge.net/projects/wxpython/files/wxPython/2.8.11.0/
4. Install robotframework-2.7.7.win32.exe, refer to: https://code.google.com/p/robotframework/downloads/list
5. Install robotframework-ride-1.1.win32.exe, refer to: https://code.google.com/p/robotframework-ride/downloads/list 
6. Double click ez_setup.py to install setuptools, refer to: https://pypi.python.org/pypi/setuptools/0.9.8#installation-instructions
7. Install pip from command line: pip install --upgrade setuptools, refer to: http://www.pip-installer.org/en/latest/installing.html
8. Install Selenium2Library from conmmand line: pip install robotframework-selenium2library, refer to: https://github.com/rtomac/robotframework-selenium2library	
9. Place IEDriverServer.exe and ChromeDriver.ext to C:\python27 to support IE and Chrome browser,
refer to: https://code.google.com/p/selenium/downloads/list and http://chromedriver.googlecode.com/ and 
