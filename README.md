# biocro/boost

## Overview

This repository contains a subset of the Boost C++ libraries for use in BioCro.

Boost does not assure backward compatibility, so changes to Boost could break
BioCro. Thus, we don't want to link our code to a user supplied Boost
installation, and we include a version with BioCro instead. Boost is very large,
so we want to include only the necessary parts.

See `NEWS.md` for more details.

BioCro developers should see `adding_the_boost_libraries.md` for
instructions on extracting parts of the boost libraries.

### License

The boost library is licensed under version 1.0 of the boost license. A copy
of this license is included here in the file `LICENSE_1_0.txt`.
