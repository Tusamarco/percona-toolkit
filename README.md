# Percona Toolkit
[![CLA assistant](https://cla-assistant.percona.com/readme/badge/percona/percona-toolkit)](https://cla-assistant.percona.com/percona/percona-toolkit)

*Percona Toolkit* is a collection of advanced command-line tools used by
[Percona](http://www.percona.com/) support staff to perform a variety of
MySQL and system tasks that are too difficult or complex to perform manually.

These tools are ideal alternatives to private or "one-off" scripts because
they are professionally developed, formally tested, and fully documented.
They are also fully self-contained, so installation is quick and easy and
no libraries are installed.

Percona Toolkit is developed and supported by Percona Inc.  For more
information and other free, open-source software developed by Percona,
visit [http://www.percona.com/software/](http://www.percona.com/software/).

## Installing

To install all tools, run:

```
perl Makefile.PL
make
make test
make install
```

You probably need to be root to `make install`.  On most systems, the tools
are installed in /usr/local/bin.  See the INSTALL file for more information.

## Documentation

Run `man percona-toolkit` to see a list of installed tools, then `man tool`
to read the embedded documentation for a specific tool.  You can also read
the documentation online at [http://www.percona.com/software/percona-toolkit/](http://www.percona.com/software/percona-toolkit/).
