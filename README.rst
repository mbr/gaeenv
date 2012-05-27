Create virtualenvs for Google app engine projects
=================================================
Requirements
------------
*yaml* aka `PyYaml <http://pyyaml.org>`_. Should be installed already on any
recent linux distro. That's it.

Usage:
------
.. code-block:: shell

   gaeenv myapp create
   gaeenv myapp install flask flask-wtf itsdangerous

End result will be a directory ``myapp``, containing the virtualenv, with a
subdirectory ``src`` that will have all installed packages linked as symlinks.

``gaeenv`` will also create a rudimentary ``app.yaml`` and a file ``gae.py``.
See the ``--help`` option to find out how to control these.
