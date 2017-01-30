KickThemOut
============

`KickThemOut <https://nikolaskama.me/kickthemoutproject/>`_ - **Kick Devices Off Your Network**

A tool to kick devices out of your network and enjoy all the bandwidth for yourself.
It allows you to select specific or all devices and ARP spoofs them off your local area network.

Compatible with Python 2.6 & 2.7.

Authors: `Nikolaos Kamarinakis <mailto:nikolaskam@gmail.com>`_  & `David Schütz <mailto:xdavid@protonmail.com>`_.

.. image:: https://nikolaskama.me/content/images/2017/01/kickthemout.png

Dependencies
-------------

KickThemOut use **python2** and won't work with **python3**. 

Installation
-------------

You can download KickThemOut by cloning the `Git Repo <https://github.com/k4m4/kickthemout>`_ and simply installing its requirements::

    $ git clone https://github.com/k4m4/kickthemout.git
    
    $ cd kickthemout/
    
    $ sudo pip install -r requirements.txt

**Note:** If you are using a distribution that is using **python3** as default, you will need to use **pip2** instead of just **pip** (that will link to **pip3**).

Mac OS X Installation
----------------------

If you would like to install KickThemOut on a Mac, please run the following::

    $ sudo pip install pcapy
    
    $ brew install libdnet scapy

**Keep in mind** that you might be asked to run some commands after executing the previous step. Moving on::

    $ git clone https://github.com/k4m4/kickthemout.git

**NOTE**: You need to have `Homebrew <http://brew.sh/>`_ installed before running the Mac OS installation.

Demo
-----

Here's a short demo:

.. image:: https://nikolaskama.me/content/images/2017/01/kickthemout_asciinema.png
   :target: https://asciinema.org/a/98200?autoplay=1&loop=1

(For more demos click `here <https://asciinema.org/~k4m4>`_.)

Disclaimer
-----------

KickThemOut is provided as is under the MIT Licence (as stated below). 
It is built for educational purposes only. If you choose to use it otherwise, the developers will not be held responsible. 
In brief, do not use it with evil intent.

License
--------

Copyright (c) 2017 by `Nikolaos Kamarinakis <mailto:nikolaskam@gmail.com>`_ & `David Schütz <mailto:xdavid@protonmail.com>`_. Some rights reserved.

KickThemOut is under the terms of the `MIT License <https://www.tldrlegal.com/l/mit>`_, following all clarifications stated in the `license file <https://raw.githubusercontent.com/k4m4/kickthemout/master/LICENSE>`_.


For more information head over to the `official project page <https://nikolaskama.me/kickthemoutproject/>`_.
You can also go ahead and email me anytime at **nikolaskam{at}gmail{dot}com** or David at **xdavid{at}protonmail{dot}com**.
