# From Inkscape #

  1. Save drawing as PostScript (.ps)
  1. Run pstoedit.exe on it like so:
> `"C:\Program Files\pstoedit\pstoedit.exe"  -xscale 1.3717 -yscale 1.3717 -f plot-hpgl %1.ps %1.hp`

# Plotting #
The serial port should be set to 115200-8-N-1, RTS/CTS flow control. The .hp file can be just copied to the port, or a program like RealTerm can be used to send data to port.