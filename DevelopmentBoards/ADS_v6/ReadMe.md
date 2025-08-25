# This is work in progress

This folder contains files related to the ADS.

ADS consists of two parts:
1. Sanket Deployment Board
2. Resistor Board

The Sanket Deployment Board contains the files of the main board which houses the regulators for heating nichrome. The Resistor board is a small vertical board that holds the nichrome wires and detector switches.

# Changes in v6 over v5
- The burnwires are in series now to prevent excess current
- The R6 can connect the EN to the voltage regulator directly, enabling easy bypassing of the current limiter

# Errata
- The R12 of the Deployment board (ILIM resistor) should be around 90 kOhm.
