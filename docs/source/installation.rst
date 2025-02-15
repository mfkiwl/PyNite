============
Installation
============

Pynite can be installed via ``pip`` (Python's default package installer). Run the following command
from the command line:

.. code-block:: console

    $ pip install PyNiteFEA

Be sure to install ``PyNiteFEA`` rather than ``PyNite``. The second one is a different package that
has nothing to do with finite element analysis.

For engineers who may be new to Python, the ``$`` symbol in the line above represents any directory
in your system that ``pip`` is accessible from. If you placed Python on your system ``PATH`` during
installation (recommended) you can run ``pip`` from any directory (see below). Otherwise it's sitting in the ``Scripts``
folder in the directory where Python was installed, and you'll need to either add it to your system
``PATH`` or navigate to that directory via the console and run the ``pip`` command above.

.. figure:: ../img/pip_installation_example.png

Dependencies
============

PyNite requires a few other dependencies to be installed in order to use it.