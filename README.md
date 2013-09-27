SingleCellAssay
===============

Infrastructure and Tools for Single Cell Assay Analysis


Installation Instructions
------------
     install.packages('devtools')
     library(devtools)
     install_github('SingleCellAssay', 'RGLab')


New Features 
------------
- Migrated underlying data storage DataLayer
- Added parallel support for reading Nanostring RCC files using foreach and dopar
- Hurdle Model implemented in zlm.SingleCellAssay
- Thresholding support for NanoString in thresholdNanoString

Bug Fixes
----------
- Fixed indexing of SingleCellAssay with an empty i index using [[

