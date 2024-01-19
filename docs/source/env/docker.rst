Docker
========

Manage Docker as a non-root user
------------------------------------

Add your user to the ``docker`` group:

.. code-block:: bash

    sudo usermod -aG docker $USER
