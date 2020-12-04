# MRCS-cpNode
## License: Creative Commons Attribution-NonCommercial-ShareAlike

cpNode and I/O expander (IOX) boards have been updated to version
2.6. Based on customer feedback, and our design and installation
experience, the changes were made to provide more efficient and
flexible physical layout of some components.

  * Rev 2.6 boards are 100% backward compatible with current versions. No software changes are needed.

Version 2.6 brings the following improvements to the proven cpNode design:

  * CMRInet interface connection has been made consistent with five position pads (R+, R-,T+,T-,SHLD).for 3.5mm screw terminals, we've removed some rarely used configurations
  * Input/Output pads moved .2" back from edge for better DIN rail clearance. The I/O option pad area accepts standard DIP component headers with 0.4" pad spacing.
  * Gnd/LED Com pads aligned to .1" (2.54 mm) for a screw terminal block or male header pins
  * Removed rarely ordered on board stall motor driver option


What does a cpNode do?

cpNodes provide input and output (I/O) ports which connect to LEDs
for signals, push buttons, turnout motors, block detectors, and
other devices to a central computer for controlling model railroads.
cpNodes may also be used as standalone controllers for staging,
crossings and interlocking plants.

You must provide a Bread Board Leonardo (BB-Leo) processor, available
from Modern Device, use coupon code "cpnode"  (DO NOT order the
header kit as headers for the BB-Leo are included in all assembled
cpNode configurations.) or order the "cpNode 2.5 LE" which includes
the BB-Leo

A cpNode has:

  * 16 I/O lines with solder pads for LED limiting resistors
  * Screw terminal blocks or solder pads to connect external devices - see configurations below
  * CMRInet RS-422/485 Network Interface.  CMRInet is now NMRA Layout Control Specification S9-10
  * I2C interface for adding Input/Output Expander (IOX) boards for more i/o ports
  * All the i/o needed to control one end of a CTC siding, just add signals and detectors and switch motor drivers
  * Female headers to receive a BB-Leo (Arduino) processor available from Modern Device, use coupon code "cpnode" or order the cpNode LE option
  * I/O is configured in 8 bit groups, providing up to 144 lines when fully expanded with IOX16s and/or IOX32s
  * Use cpNodes as small, economical, CMRI nodes as is or customize the code to support applications requiring local intelligence
  * BB-Leo uses the Atmel Atmega32u4 processor chip, see the data sheet for electrical characteristics
  * Standard "Sketch" (Arduino program) is compatible with JMRI or traditional CMRI BASIC/Visual Basic development tools

