# Visionary 3D Model Library
The Visionary library contains 3D models in the areas of astronomy, microscopy, photography and electronics.
It uses scad-clj to generate OpenSCAD models which can then be exported to STL or other file formats supported by OpenSCAD.

# Rationale
OpenSCAD is a nice tool to programatically generate 3D models, e.g. for printing with 3D printers.
But the SCAD language is a description language, not a real programming language.

With [scad-clj](https://github.com/farrellm/scad-clj) models can be created in clojure and rendered as SCAD files to be displayed by OpenSCAD.


# Copyright
© Ludger Solbach

# License
LGPL-2.1

# Getting Started
To use the Visionary OpenSCAD library, extract/copy the directory "visionary" to the libs folder of your OpenSCAD installation.

# Project Structure
The project has the following directory layout
* Root directory
  * Basic library files
* visionary/<domain> (astronomy, microscopy, photography, etc)
  * Domain specific library files
* visionary/models
  * Concrete. printable models created with the modules from the library 
* visionary/docs
  * General documentation for the visionary library

# Dependencies
Currently no dependencies.
