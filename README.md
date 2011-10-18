Laptop
======

Laptop is a set of scripts to get your laptop set up as a development machine.

Mac OS X
--------

First, install [GCC for OS X](https://github.com/kennethreitz/osx-gcc-installer). (requires OS X 10.6 or higher)
XCode will be installed.

Then, run this one-liner:

    bash < <(curl -s https://raw.github.com/crakalakin/laptop/master/mac)

Ubuntu
------

Run this one-liner:

    bash < <(curl -s https://raw.github.com/crakalakin/laptop/master/ubuntu)

(From thoughtbot:)
If you're setting up Ubuntu for one of our workshops, we recommend you also install gEdit for your text editor.
You can [customize it with these instructions](http://blog.sudobits.com/2011/04/02/textmate-for-ubuntu-linux/).

What it sets up
---------------

* SSH public keys (for authenticating with services like Github and Heroku)
* Homebrew or apt-get (for managing operating system libraries)
* Postgres (for storing relational data)
* ImageMagick (for cropping and resizing images)
* RVM (for managing versions of the Ruby programming language)
* Ruby 1.9.2 stable (for writing general-purpose code)
* Bundler gem (for managing Ruby libraries)
* Rails gem (for writing web applications)
* Heroku gem (for interacting with the Heroku API)
* Taps gem (for pushing and pulling SQL databases between environments)
* Postgres gem (for making Ruby talk to SQL databases)

It should take about 30 minutes for everything to install, depending on your machine.
