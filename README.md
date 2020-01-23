# Digital IDentity and Authorization protocol

This is the working area for the individual Internet-Draft, "Digital IDentity and Authorization protocol".

* [Editor's Copy](https://dickhardt.github.io/hardt-DIDAP-protocol/draft-hardt-DIDAP-protocol.html)
* [Individual Draft](https://tools.ietf.org/html/draft-hardt-DIDAP-protocol) NOT YET THERE!

## Building the Draft

Formatted text and HTML versions of the draft can be built using `make`.

```sh
$ make
```

This requires that you have the necessary software installed.  See
[the instructions](https://github.com/martinthomson/i-d-template/blob/master/doc/SETUP.md).


## Contributing

See the
[guidelines for contributions](https://github.com/dickhardt/hardt-DIDAP-protocol/blob/master/CONTRIBUTING.md).

## auto reloading on Mac OS
Notes so I remember how to do this! :)

    brew install watchexec
    npm install -g reload

    watchexec -c make

    reload -b -s draft-hardt-DIDAP-protocol.html 