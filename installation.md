---
layout: page
title: Installation
---
{% include JB/setup %}

## Installation

For installing *jpylyzer*, you have three options:

1. Install with the *Pip* package manager. This works on all platforms
(Windows, Linux, Mac, etc.), but you need to have the Python interpreter
available on your system. *Jpylyzer* is compatible with Python 2.7, and Python
3.2 and more recent (Python 3.0 and 3.1 are not supported).

2. Alternatively, for Windows users stand-alone binaries are available.
These allow you to run *jpylyzer* as anexecutable Windows application,
without any need for installing Python. This option is particularly useful
for Windows users who cannot (or don’t want to) install software on their system.

3. For Linux users Debian packages are available. These allow you to run
*jpylyzer* without any need for installing Python.

These options are briefly outlined below. See the [User Manual]({{ BASE_PATH }}/userManual.html)
for a more exhaustive description.

## Installation with Pip (all platforms)

First make sure you have a recent version of *pip*. Then install *jpylyzer*
with the following command:

    pip install jpylyzer

This may require administrator/super user privileges. If you don't have these
privilges, you can do a single-user install:

    pip install jpylyzer --user

## Windows binaries

Download the binary (64 or 32 bit) using the link using the link in the right-hand bar of
this page. Unzip the contents of this file to an empty folder on your PC. *Jpylyzer* should
now be ready for use.

Optionally, you may also want to add the full path of the *jpylyzer*
installation directory to the Windows ’Path’ environment variable. Doing
so allows you to run *jpylyzer* from any directory on your PC without
having to type the full path. In Windows 7 you can do this by selecting
‘settings’ from the ‘Start’ menu; then go to ‘control panel’/’system’
and go to the ‘advanced’ tab. Click on the ‘environment variables’
button. Finally, locate the ‘Path’ variable in the ‘system variables’
window, click on ‘Edit’ and add the full *jpylyzer* path (this requires
local Administrator privileges). The settings take effect on any newly
opened command prompt.

## Installation from Debian packages (Linux)

For a number of Linux architectures Debian packages of *jpylyzer* exist.
To install, download the package for your architecture using the link in the right-hand bar of
this page, and then open it with your package manager (which can be invoked by double-clicking
or right-clicking on the *.deb* file). Alternatively you can also do this in the
command terminal by typing:

    sudo dpkg -i jpylyzer_1.18.0_amd64.deb

For *Ubuntu* and *Debian*, alternative packages are available in the
official release channels. To install simply run the following commands:

    sudo apt-get update
    sudo apt-get install python-jpylyzer

In both cases you need to have superuser privileges.

A more exhaustive description of the above installation options can be found in the [User Manual]({{ BASE_PATH }}/userManual.html).