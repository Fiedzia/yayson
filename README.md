yayson
======

Yay! Beautiful JSON on the command line!

`yayson` will take input on `stdin` and print pretty JSON with color in your terminal. It will come out something like this:

![Example Yayson output](http://sebdah.github.com/yayson/img/screenshot.png)

Example usage
-------------

    cat my.json | yayson

or

    curl -s http://www.example.com/my.json | yayson

--help output
-------------

    usage: yayson [-h] [-i INDENT] [-s]

    Yayson produces beautiful JSON

    optional arguments:
      -h, --help            show this help message and exit
      -i INDENT, --indent INDENT
                            Number of spaces to indent with (default: 4)
      -s, --sort            Turn on key sorting

Release information
-------------------

**0.1.1 (2013-04-07)**

- Initial release

Releasing to PyPI
-----------------

    make release

Author
------

This project is maintained by [Sebastian Dahlgren](http://www.sebastiandahlgren.se) ([GitHub](https://github.com/sebdah) | [Twitter](https://twitter.com/sebdah) | [LinkedIn](www.linkedin.com/in/sebastiandahlgren))