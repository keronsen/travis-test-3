# Appstax CLI 

Command-line client for appstax.com


### Building 

You need [go](http://golang.org/) and [goxc](http://github.com/laher/goxc) to build appstax-cli. Go is available from Homebrew: `brew install go`, and goxc can be installed with `go get github.com/laher/goxc`

Run `./build.sh` to compile for your current platform. You will find the built artifacts in `.godeps/bin`

Run `./build.sh XC` to cross-compile. Built artifacts in `.godeps/bin/appstax-xc/snapshot`

### Running

`cd .godeps/bin`, then `appstax --help` to show available options.
