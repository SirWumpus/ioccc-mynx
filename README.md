
I was rather impressed by last year's mini web server. So much so that it inspired me to try my hand at writing the client side complement. 

A typical build would be command would be:

    $ gcc -omynx mynx.c

While some others like to be a little different:

    $ gcc -omynx mynx.c -lnsl -lsocket 

I even managed to figure out a basic configure script, given last year's example, which is kinda of useful when you consider how many OSes put all the network functions in a variety of places. So a simpler build command sequence would be:

    $ ./configure
    $ make

After which, the rest of the documentation can be read by saying:

    $ mynx manual.html


Manifest:

    mynx.c
    makefile            pre-built generic Un*x
    README.md
    manual.html
    makefile.in         makefile template
    entities.txt        ISO 8859-1 entites
    configure.in        configure script description
    configure           pre-built configure script




