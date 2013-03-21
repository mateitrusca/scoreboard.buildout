===================
scoreboard.buildout
===================
Scoreboard installation kit based on zc.buildout_

Install
=======
::

    $ git clone git@github.com:eaudeweb/scoreboard.buildout.git
    $ cd scoreboard.buildout
    $ virtualenv2.6 .
    $ source bin/activate

    $ bin/python boostrap.py -d -c devel.cfg
    $ bin/buildout -c devel.cfg

.. _zc.buildout: http://pypi.python.org/pypi/zc.buildout/1.7.1
