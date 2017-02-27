# somafm

A somafm command line client written in Perl

Install
-------

This script requires:

* libwww
* mplayer
* figlet (optionally, if you want a big title)

Install the requirements, clone this repository and copy *somafm* to the binaries directory.
On a Debian system you can:

    sudo apt-get install libwww-perl mplayer
    git clone https://github.com/david-moreno/somafm.git
    sudo cp somafm/somafm /usr/bin/

Usage
-----

On a fresh install, you must update your station's list.
You need to make this only once (or when a new station is created).

    somafm --update

Now, check the station list:

    somafm --list

When you have choosen a station, go listen it:

    somafm your-favorite-station

Not sure what to listen? Try **random**:

    somafm random

Support
-------

[Remember to support somafm!](https://somafm.com/support/)
