[![Build Status](https://travis-ci.org/SCP002/clipboard.svg?branch=master)](https://travis-ci.org/SCP002/clipboard)

[![GoDoc](https://godoc.org/github.com/SCP002/clipboard?status.svg)](http://godoc.org/github.com/SCP002/clipboard)

# Clipboard for Go

Provide copying and pasting to the Clipboard for Go.

Build:

    $ go get github.com/SCP002/clipboard

Platforms:

* OSX
* Windows 7 (probably work on other Windows)
* Linux, Unix (requires 'xclip' or 'xsel' command to be installed)


Document: 

* http://godoc.org/github.com/SCP002/clipboard

Notes:

* Text string only
* UTF-8 text encoding only (no conversion)

TODO:

* Clipboard watcher(?)

## Commands:

paste shell command:

    $ go get github.com/SCP002/clipboard/cmd/gopaste
    $ # example:
    $ gopaste > document.txt

copy shell command:

    $ go get github.com/SCP002/clipboard/cmd/gocopy
    $ # example:
    $ cat document.txt | gocopy



