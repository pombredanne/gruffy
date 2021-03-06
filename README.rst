Gruffy
======
Python Graphing Library

About
-----
Gruffy is a yet another Python Graphing Library.
inspired by `Gruff`_ (Ruby Graphing Library).

This module using `pgmagick`_ (GraphicsMagick) .

.. _`Gruff`: http://nubyonrails.com/pages/gruff
.. _`pgmagick`: http://pypi.python.org/pypi/pgmagick/


Installation
------------
Install from PyPI::

    $ pip install gruffy


Requirements
------------
`pgmagick`_ module.

package install on Ubuntu::

    $ apt-get install libgraphicsmagick++-dev
    $ apt-get install libboost-python1.40-dev
    $ pip install pgmagick


Basic Usage
-----------

Bar Graph Sample::

    from gruffy import Bar

    g = Bar()
    g.title = "Gruffy's Graph"

    g.data("Apples", [1, 2, 3, 4, 4, 3])
    g.data("Oranges", [4, 8, 7, 9, 8, 9])
    g.data("Watermelon", [2, 3, 1, 5, 6, 8])
    g.data("Peaches", [9, 9, 10, 8, 7, 9])

    g.labels = {0: '2003', 2: '2004', 4: '2005'}

    g.write('sample.png')


Documentation
-------------
`Gruffy Documentation`_

.. _`Gruffy Documentation`: http://www.hexacosa.net/documents/gruffy/


Links
-----
* PyPI_
* GitHub_
* Jenkins_

.. _PyPI: http://pypi.python.org/pypi/gruffy
.. _GitHub: http://github.com/hhatto/gruffy
.. _Jenkins: http://jenkins.hexacosa.net/job/gruffy/

