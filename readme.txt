
=Building on Windows=

=Building on Linux=

You will need Postgres and you will need the Postgres development files. On Ubuntu you will want to make sure you the right packages installed.

    $ sudo apt-get install libpq-dev

The library can be configured through running the configure script. This will also do a build to make sure that everything is as it should be.

    $ ./configure
