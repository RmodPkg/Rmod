# Rmod
An R package to generically solve dynamic models

This is the *future home* of the Rmod package for R.

# Description

The typical use case is to solve (economic) dynamic models given by a simple input text file (*.Rmod) containing the model primitives (i.e., first-order conditions, resource constraints, etc.). From the given Rmod-file Rmod generates efficient code (R and/or C++ using RcppEigen) to solve dynamic transition paths for that model. Optionally, Rmod can generate R-packages for repeated use.
