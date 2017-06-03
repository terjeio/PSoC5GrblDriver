# PSoc5GrblDriver
A Grbl driver for Cypress PSoC 5 \(CY8CKIT-059\), for my HALified library version of Grbl

** EXPERIMENTAL **

Features:

* All hardware dependent code in this project. In order to compile this projects requires my HALified Grbl library to be added, either directly to this project or as a dependency.

Some of the program logic is moved to UDMs, typically signal inversions.

**NOTE:** currently only tested on a CY8CKIT-059 prototyping kit with an oscilloscope to verify some signals. No motors connected yet!
