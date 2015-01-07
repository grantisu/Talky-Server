Talky Server
============

A quick and dirty text-to-speech server designed to be deployed on a small,
trusted network.

Install
-------

    cpanm Task::Plack Speech::eSpeak

Usage
-----

    plackup
    (turn speakers on)
    curl -s http://127.0.0.1:5000/talky?tosay=Hello > /dev/null

WARNING
-------

This is probably full of security holes.

License
-------

Everything in this repository is released into the public domain as explained
in the [CC0 license]( https://creativecommons.org/publicdomain/zero/1.0/ ).

