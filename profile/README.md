# OpenLatero

## Overview

OpenLatero is a set of open source libraries and programs for the Latero tactile display:

- **[latero](https://openlatero.org/latero)**: the low level driver for the Latero device
- **[latero-gui](https://openlatero.org/latero-gui)**: a GUI that allows the individual testing of the actuators
- **[latero-graphics](https://openlatero.org/latero-graphics)**: a library for tactile rendering
- **[latero-demo](https://openlatero.org/latero-demo)**: a program that makes use of the latero-graphics library and showcases the Latero device's functionality
- **[latero-graphics-studio](https://openlatero.org/latero-graphics-studio)**: a program that allows editing of 2D tactile graphics rendered using the latero-graphics library
- **[latero-graphics-demo](https://openlatero.org/latero-graphics-demo)**: a program that makes use of the latero-graphics library and showcases the Latero device's functionality when mounted on a 2D slider (Tactograph)

Most are released under the terms of the MIT License. The example programs included with the latero and latero-graphics libraries are released in the public domain.

## Getting Started

1. Install the [latero](https://openlatero.org/latero) library, following the instructions in its README.
2. Try the [latero examples](https://github.com/OpenLatero/latero/tree/master/examples), starting with [01-vibrate-loop](https://github.com/OpenLatero/latero/tree/master/examples/01-vibrate-loop), which makes the pins of the Latero vibrate.
3. To render tactile graphics, install the [latero-graphics](https://openlatero.org/latero-graphics) library and try the [latero-graphics examples](https://github.com/OpenLatero/latero-graphics/tree/master/examples): [01-vibrate-engine](https://github.com/OpenLatero/latero-graphics/tree/master/examples/01-vibrate-engine) produces the same vibration using a tactile engine, and [02-vibrate-gui](https://github.com/OpenLatero/latero-graphics/tree/master/examples/02-vibrate-gui) adds a GUI.

Each example is a small standalone project built against the installed libraries, and can be freely copied as a starting point for your own programs.

## Releases

The `master` branch of each project is under active development and may include breaking changes. For a stable version, use the latest release of each project (see its Releases page on GitHub). All projects share the same version number, and releases with the same version are meant to be used together. Release v0.0.0 of each project preserves the code as it was before development resumed in 2026.

## Supported Platforms

OpenLatero is primarily developped and tested on macOS but should also run on Linux and Windows. Please see instructions in each individual project.

OpenLatero was tested in October 2026 on macOS 27.0, Linux Ubuntu 26.04 and Windows 11.

## About the Latero Tactile Display

The Latero device is distributed by the not-for-profit organization [Tactile Labs Inc.](http://tactilelabs.com).
It was previously named STReSS and was originally designed at the [McGill Haptics Laboratory](http://www.cim.mcgill.ca/~haptic/).
Videos of the device in action, as well as a list of related publications, can be found [here](http://www.cim.mcgill.ca/~haptic/laterotactile/dev/stress/).
Please refer to Vincent Levesque's 2009 Ph.D. thesis ["Virtual Display of Tactile Graphics and Braille by Lateral Skin Deformation"](http://vlevesque.com/go/phd.html) for an in-depth report on the design, implementation and experimental evaluation of multiple tactile renderers developed specifically for the STReSS device.

## Authors

OpenLatero is maintained by [Vincent Levesque](https://vlevesque.com) and his Haptic User Experience research group at [École de technologie supérieure](https://etsmtl.ca). It was originally developped as part of his PhD thesis at [McGill University](https://mcgill.ca) and prepared for release as as open source project by Jerome Pasquero (<jerome.pasquero@gmail.com>). Please see the git history for a full list of contributors.
