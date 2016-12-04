go-fish
======

A [><>](esolangs.org/wiki/Fish) interpreter written in Go.

Installation
---------------

Install [golang](http://golang.org/doc/install). To install or update the package draw2dui on your system, run:

```
go get -u github.com/redstarcoder/go-fish
```

Usage
---------------

```
$ go-fish -h
Usage: go-fish [args] <file>
  -c	outputs the codebox each tick
  -h	displays this help message
  -i value
    	sets the initial stack (ex: '"Example" 10 "stack"')
  -s	outputs the stack each tick
  -t duration
    	time to sleep between ticks (ex: 100ms)
```

Acknowledgments
---------------

* [redstarcoder](https://github.com/redstarcoder) wrote this library.