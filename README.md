# Rakemaker

Rakemaker consists of a simple Makefile which attempts to forward Make targets to Rake.

**It's kind of pointless...**

## Use Case

Let's say you type in `$ make target`, when you realy should have typed `$ rake target`.  Rakemaker saves you! :D

## Options

Option handling/forwarding is non-existent. Don't even try. It won't work.

## Rakefile

An example Rakefile is provided, as a demo.  It echoes back any target it is called on.

## License

This really doesn't need a license, but just in case, The MIT License (MIT) applies (see LICENSE.md).
Essentially, use Rakemaker for whatever you want, but don't blame me if anything goes wrong...