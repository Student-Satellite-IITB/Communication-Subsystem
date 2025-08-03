This folder contains files related to the ADS.

ADS consists of two parts:
1. Sanket Deployment Board
2. Resistor Board

The Sanket Deployment Board contains the files of the main board which houses the regulators for heating nichrome. The Resistor board is a small vertical board which hold the nichrome wires and detector switches.

# Changes in v5 over v4
- Constant voltage regulator as opposed to the adjustable voltage
- Current limiter supplies nichrome as opposed to voltage regulator
- Number of pin changed in supply diagram
- Board now accepts 12V
- Deployment switch added
- Number of pins on the resistor board changed, now in a 6 pins single row
- Traces are now extra wide (7.2 mm → 1.5 mm)
- Added an extra cut to accomodate the coaxial cable

# Improvements needed in v5
- The TPS25200 enable high means the current is disables
- If the nicrhome wires are used in series, current limiter can be eliminated
- There is no compensation network on the switching converter (F)
