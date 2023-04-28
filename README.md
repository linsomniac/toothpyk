# Toothpyk -- Small Self-Contained Tools

Think "Swiss Army Toothpick", a bunch of small, self-contained tools oriented towards
the python sysadmin.  Something you can "wget" onto a rescue image or download to
your ~/bin directory to give you little tools.

## Sub-commands

- allow               Allow a connection through the firewall.
- eval (e)            Evaluate a Python expression and return the result.
                    Can be used as a simple infix calculator.
- modulefile (mf, modfile)
                    Print out the "__file__" attribute of the specified
                    module, so you can take a peek at the source.
- send                Connect to a socket and send data to it.
- split               Filter to read stdin/file and print the specified
                    columns.
- receive (recv)      Listen on a socket and when a connection comes in read
                    data from it.
- rsend               Listen on a socket and when a connection comes in send
                    data to it.
- rreceive (rrecv)    Connect to a socket and read data from it.
- random              Print out a random number.
- rpncalc (rc, rpn)   An RPN desk calculator, use comma like Enter and 'x'
                    can be used for multiply.
- zoneoffset (z)      Print the current timezone offset from GMT.

## Requirements

- Python 3

## License

CC0 1.0 Universal, see LICENSE file for more information.

<!-- vim: ts=4 sw=4 ai et tw=85
-->
