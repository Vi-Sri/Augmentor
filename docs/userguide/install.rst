Installation
============

Installation is via ``pip``:

.. code-block:: python

    pip install Augmentor

If you have to use ``sudo`` it is recommended that you use the ``-H`` flag:

.. code-block:: python

    sudo -H pip install Augmentor

Requirements
------------

Augmentor requires ``terminaltables`` and ``Pillow``.

Building
--------

If you prefer to build the package from source, first clone the repository: 

.. code-block:: bash

    git clone https://github.com/mdbloice/Augmentor.git

Then enter the ``Augmentor`` directory and build the package:

.. code-block:: bash

    cd Augmentor
    python setup.py install 

Alternatively you can first run ``python setup.py build`` followed by ``python setup.py install``. This can be useful for debugging.