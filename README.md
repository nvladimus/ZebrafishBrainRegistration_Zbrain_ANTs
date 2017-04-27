# Zebrafish brain registration to the Z-Brain atlas
Rigid and non-rigid (SyN) registration using [ANTs](http://stnava.github.io/ANTs/) registration tools, wrapped into an IPython notebook.

Zebrafish brains expressing GCaMP6f were imaged live with [Zebrascope](https://www.nature.com/nmeth/journal/v11/n9/full/nmeth.3040.html)
light-sheet microscope and down-sampled (5 microns/px in XYZ) to speed up calculations.
Data from 3 fish pre- and post-ablation of nMLF neurons are given as examples. 
Raw data includes reference fluorescence stacks `ref.nrrd` and pre-processed dFF activity stacks `meanActivity_Fstim.nrrd`

The reference Z-Brains were downloaded from [Z-Brain official page](http://engertlab.fas.harvard.edu/Z-Brain/about.html), down-sampled and converted to NRRD format using [ImageJ/FIJI](https://fiji.sc/).

The code was tested on Windows 7, [Anaconda](https://docs.continuum.io/anaconda/install) Python 2.7 distribution.
