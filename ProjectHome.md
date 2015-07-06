# About #

**Termite Scheme** is a variant of Scheme intended for distributed computing. It offers a simple and powerful concurrency model, inspired by the Erlang programming language, which is based on a message-passing model of concurrency.

There's a [paper](http://termite.googlecode.com/files/termite.pdf) about Termite.

It runs on top of [Gambit-C](http://www.iro.umontreal.ca/~gambit), a very nice Scheme system developed by Marc Feeley at Université de Montréal.

# License #

Termite is distributed under the terms of the LGPL license.

# Installation #

#1 Install the latest version of Gambit-C

#2 Get the latest Termite and put it in Gambit's lib/ directory

```
$ cd /usr/local/Gambit-C/current/lib
$ svn checkout http://termite.googlecode.com/svn/trunk/ termite
```


#3 Copy the `tsi` script to Gambit's bin directory (optional)

# Contact #

Questions and comments can be sent to Guillaume Germain (guillaume.germain at gmail.com).  Please use [Issues](http://code.google.com/p/termite/issues/list) for feature request and bug reports.