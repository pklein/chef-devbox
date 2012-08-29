chef-devbox
===========

This project is to push a base config for my base linux system setup. I can't believe I've just been brainlessly repeating the same process everytime I need to install, always running into new and annoying issues. Hopefully using this will prevent me from forgetting my custom fixes and setup on various different machines.

Prerequisites
-------------

* Chef
* librarian-chef


To run
------

    sudo chef-solo -c config/solo.rb -j config/node.json
    librarian-chef install
