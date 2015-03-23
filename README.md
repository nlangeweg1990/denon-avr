Denon AVR Remote Library
====

Simple library that provides a channel based communication
with a Denon AVR. Most importantly does event assembly from
multiple messages and sends them to the caller in generic
[]byte slices.

An example application for use on the command line is provided
in denon/ which uses readline for command line editing and
completion.

Installation
----

`go install github.com/fritschy/denon-avr/denon` To install
the command line utility, or just
`go install github.com/fritschy/denon-avr/davr` if only the
*library* is needed.