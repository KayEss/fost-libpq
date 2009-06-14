
=Building on Windows=

No explicit build step is required on Windows, although Postgres 8.3 is required and the development options must also be installed.

If you're not using the Fost libraries then you'll want to take a look at the Jamfile for fost-postgres/Cpp/fost-pqxx to show you how to build libpqxx.

=Building on Linux=

You will need Postgres and you will need the Postgres development files. On Ubuntu you will want to make sure you the right packages installed.

    $ sudo apt-get install libpq-dev

The library can be configured through running the configure script. This will also do a build to make sure that everything is as it should be.

    $ ./configure
