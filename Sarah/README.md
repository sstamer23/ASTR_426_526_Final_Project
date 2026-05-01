# Sarah's Code Folder
This folder has Sarah's code and data for the project.

Test.ipynb looks for a close match in APOGEE for a few select Gaia coordinates. If the coordinates are not an exact match, it will find the closest APOGEE coordinates to those from Gaia. 

Spectra.ipynb downloads the APOGEE spectra for the given IDs that correspond to the Gaia samples. After downloading the spectra, it performs spectral extraction and plots the spectra as png files. 

Histograms.ipynb uses the Gaia non_single_star flag to plot histograms of the frequency of single star solutions and of different types of binaries. It also shows the RUWE cut for binarity on the histograms, and determines what percent of the single stars/binaries by type exceed the RUWE cut value. 

NOTE: To download the allStar-dr17-synspec_rev1.fits file, see https://data.sdss.org/sas/dr17/apogee/spectro/aspcap/dr17/synspec_rev1/allStar-dr17-synspec_rev1.fits. 
