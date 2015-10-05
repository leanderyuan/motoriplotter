# Introduction #

HPGL is a very complex language. Motöri only implements a limited subset of it, and even those instructions that are listed as supported don't implement all possibilities or quirks.


# List of supported commands #

Currently only the following commands are supported:
  * IP: input P1 and P2, SC: scale
  * IN: init, PG: page eject/end plot
  * SP: (select pen)
  * PU, PD: pen up/down
  * AA: arc absolute
  * SR: character size relative
  * SI: character size absolute in cm
  * DT: label terminator char (default ETX, \003)
  * DI: label direction (run, rise)
  * LB: text label

# External References #
[Isoplotec HP/GL Reference Outline](http://www.isoplotec.co.jp/HPGL/eHPGL.htm)