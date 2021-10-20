
# Installation

Installation of OpenJML is simple:

* Download the current release (in the 16.* or higher series, not the 8.* series) from [here](https://openjml.github.com/releases/latest).
* Unzip the downloaded .zip file
* The contents of the .zip file (e.g., the `openjml` executable) should be in
a clean directory, though the location and name of the directory are up to the user (though spaces in the folder name or path are not permitted).
* The executable is the script named `openjml` in the top-level of the 
installation. Do not move or rename this file, but you may make a link to the
file or place it on your system PATH.
* OpenJML is a modified version of the OpenJDK `javac`. It is a standalone, 
encapsulated executable; no installation of Java is needed to run it.

You can check that the installation is working by running `openjml -version`.
Instructions on running `openjml` and executing the tutorial examples are
[here](Execution).