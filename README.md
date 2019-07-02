# CESM

Using this as the base for the CESM2 nuopc cap WW3

From model/bin directory: 
./w3_setup /glade/u/home/hkershaw/WW3.shel/model -c Intel -s cici

   Modified set up :
      Printer (listings)       : printer
      Auxiliary FORTRAN comp.  : ifort
      Auxiliary C compiler     : icc
      Scratch directory        : /glade/u/home/hkershaw/WW3.shel/model/tmp
      Save sources             : yes
      Save listings            : yes

./w3_automake

model/tmp_MPI contains the *.F90 files

# The WAVEWATCH III Framework

WAVEWATCH III &reg; is a community wave modeling framework that includes the 
latest scientific advancements in the field of wind-wave modeling and dynamics.

## General Features

WAVEWATCH III<sup>&reg;</sup> solves the random phase spectral action density 
balance equation for wavenumber-direction spectra. The model includes options 
for shallow-water (surf zone) applications, as well as wetting and drying of 
grid points. Propagation of a wave spectrum can be solved using regular 
(rectilinear or curvilinear) and unstructured (triangular) grids. See 
[About WW3](https://github.com/NOAA-EMC/WW3/wiki/About-WW3) for a 
detailed description of WAVEWATCH III &reg;.

## Installation

The WAVEWATCH III framework package has two parts that need to be combined so 
all runs smoothly: the GitHub repo itself, and a binary data file bundle that 
needs to be obtained from our ftp site. Steps to successfully acquire and install 
the framework are outlined in our [Quick Start](https://github.com/NOAA-EMC/WW3/wiki/Quick-Start)
guide.

## Disclaimer

The United States Department of Commerce (DOC) GitHub project code is provided
on an 'as is' basis and the user assumes responsibility for its use. DOC has
relinquished control of the information and no longer has responsibility to
protect the integrity, confidentiality, or availability of the information. Any
claims against the Department of Commerce stemming from the use of its GitHub
project will be governed by all applicable Federal law. Any reference to
specific commercial products, processes, or services by service mark,
trademark, manufacturer, or otherwise, does not constitute or imply their
endorsement, recommendation or favoring by the Department of Commerce. The
Department of Commerce seal and logo, or the seal and logo of a DOC bureau,
shall not be used in any manner to imply endorsement of any commercial product
or activity by DOC or the United States Government.

