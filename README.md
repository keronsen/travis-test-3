

### Pre-release note

Please note that this repository contains pre-release software, and cannot be used until the Appstax services are officially released. Want beta access? [Send us an email](ea@appstax.com) to request an early access code.


Appstax CLI 
===========

This is the official command-line application [Appstax](http://appstax.com).


Installing
----------

*On Mac OSX*, install the latest version from the terminal:

```bash
curl -s http://appstax.com/download/cli/install_osx.sh | sudo /bin/bash
```

*On Linux*:

```bash
curl -s http://appstax.com/download/cli/install_linux.sh | sudo /bin/bash
```

*On Windows*, [download the latest release](https://github.com/appstax/appstax-cli/releases/latest) and copy appstax.exe into `c:\Windows\System32`.

*For any system* you can also [download the latest release](https://github.com/appstax/appstax-cli/releases/latest) and manually copy the appropriate binary to somewhere on your systems `PATH`.


### Building 

You need [go](http://golang.org/) and [goxc](http://github.com/laher/goxc) to build appstax-cli. Go is available from Homebrew: `brew install go`, and goxc is automatically installed when running the build.

Run `./build.sh` to compile for your current platform. You will find the built artifacts in `.godeps/bin`

Run `./build.sh XC` to cross-compile. Built artifacts in `.godeps/bin/appstax-xc/snapshot`

### Running

`cd .godeps/bin`, then `appstax --help` to show available options.


License
-------

[MIT License](LICENSE)


