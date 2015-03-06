++++++++++++
Installation
++++++++++++

Binary Installers
=================

Nightly build installers are available for Linux and Mac OS and may be
downloaded from http://cci.lbl.gov/dials/installers/ and
http://dials.diamond.ac.uk/builds/.  Builds for Microsoft Windows are not
currently available, but will be added in the near future.

For instructions on compiling from source or setting up a DIALS development
environment, see :doc:`/documentation/installation_developer`.

Mac graphical binary installers
-------------------------------

We provide a graphical package installer for Mac users. Download, e.g., the
file ``dials-dev-239-mac-intel-osx-x86_64.pkg.zip``, double click the ``.pkg.zip``
file in Finder to unzip, then once again double click the ``.pkg`` to start the
graphical installer. Follow the instructions, which will install DIALS in
``/Applications/`` directory. To use DIALS, open a new terminal window and type,
e.g. ::

  source /Applications/dials-dev-239/dials_env.sh

to setup the DIALS environment.

Mac and Linux binary installers
-------------------------------

In addition to the Mac graphical installers, we provide binary ``tar.gz`` files
for various Mac and Linux platforms, e.g.::

  curl http://cci.lbl.gov/dials/installers/dev-239/dials-installer-dev-239-intel-linux-2.6-x86_64-centos5.tar.gz > dials-installer.tar.gz
  tar -xzf dials-installer.tar.gz
  cd dials-installer

Then to install in the /usr/local directory (you may need to add a ``sudo``
before the command)::

  ./install

or to install in a specified directory::

  ./install --prefix=/path/to/installation/directory/


Windows binary installers
-------------------------

Unfortunately we don't currently provide Windows binaries, although we do plan
to add them in due course. For instructions on building DIALS from source, see
:ref:`build_dials_windows`
