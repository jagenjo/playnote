# playnote
A simple script in nodejs to send MIDI notes sequences to a midi output.
Great to use in a Raspberry Pi connected through MIDI to any device.

Usage:

playnote

optional:
  * -p num  open port
  * -s scale selects scale, valid names are major,minor,pentatonic,chromatic,stranger
  * -t interval time between notes
  * -o octave the octave number
  * -v verbose
  * -m mode valid modes are rand,up,down,updown,walk
