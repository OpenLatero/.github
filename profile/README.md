# OpenLatero

## Overview

OpenLatero is a set of open source libraries and programs for the Latero tactile display:

- **[latero](https://openlatero.org/latero)**: the low level driver for the Latero device
- **[latero-gui](https://openlatero.org/latero-gui)**: a GUI that allows the individual testing of the actuators
- **[latero-examples](https://openlatero.org/latero-examples)**: a set of example programs using the latero or latero-graphics libraries
- **[latero-graphics](https://openlatero.org/latero-graphics)**: a library for tactile rendering
- **[latero-demo](https://openlatero.org/latero-demo)**: a program that makes use of the latero-graphics library and showcases the Latero device's functionality
- **[latero-graphics-studio](https://openlatero.org/latero-graphics-studio)**: a program that allows editing of 2D tactile graphics rendered using the latero-graphics library
- **[latero-graphics-demo](https://openlatero.org/latero-graphics-demo)**: a program that makes use of the latero-graphics library and showcases the Latero device's functionality when mounted on a 2D slider (Tactograph)

Most are released under the terms of the MIT License. The latero-examples are released in the public domain.

## Supported Platforms

OpenLatero is primarily developped and tested on MacOS but should also run on Linux and Windows. Please see instructions in each individual project.

OpenLatero was tested in May 2026 on MacOS Tahoe 26.5 with [MacPorts](https://www.macports.org) 2.12.5. It has not been recently tested on Windows or Linux.

## About the Latero Tactile Display

The Latero device is distributed by the not-for-profit organization [Tactile Labs Inc.](http://tactilelabs.com).
It was previously named STReSS and was originally designed at the [McGill Haptics Laboratory](http://www.cim.mcgill.ca/~haptic/).
Videos of the device in action, as well as a list of related publications, can be found [here](http://www.cim.mcgill.ca/~haptic/laterotactile/dev/stress/).
Please refer to Vincent Levesque's 2009 Ph.D. thesis ["Virtual Display of Tactile Graphics and Braille by Lateral Skin Deformation"](http://vlevesque.com/go/phd.html) for an in-depth report on the design, implementation and experimental evaluation of multiple tactile renderers developed specifically for the STReSS device.

## Authors

OpenLatero is maintained by [Vincent Levesque](https://vlevesque.com) and his Haptic User Experience research group at [École de technologie supérieure](https://etsmtl.ca). It was originally developped as part of his PhD thesis at [McGill University](https://mcgill.ca) and prepared for release as as open source project by Jerome Pasquero (<jerome.pasquero@gmail.com>). Please see the git history for a full list of contributors.
