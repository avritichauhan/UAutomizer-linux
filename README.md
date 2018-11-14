# UAutomizer-linux

Copyright (C) 2012-2017 University of Freiburg

* The UAutomizer-linux package has been downloaded from the below link
	https://github.com/ultimate-pa/ultimate/releases/download/v0.1.23/UltimateAutomizer-linux.zip
  The following changes are done in the downloaded package:
	- Removed the following binaries and corresponding licenses:
		- cvc4
		- cvc4-LICENSE
	- Added the following binaries and corresponding licenses:
		- mathsat-LICENSE: With permission from MATHSAT team to use MathSAT within VeriAbs for SV-COMP 2019 (https://sv-comp.sosy-lab.org/2019/) only.
		- cvc4: A version of CVC4(binary) that uses no GPLed libraries, by configuring it with "--bsd" option. (Build steps: https://github.com/CVC4/CVC4/blob/master/INSTALL.md)
		- cvc4-LICENSE: Modified BSD
