RAISIN Data Release
===================

This repository contains photometry and distance measurements for the RAISIN sample (HST-GO 13046 and 14216) along with low-z photometry/distance measurements from the Carnegie Supernova Project third data release.  The analysis of these data is published in Jones et al. (2022), ApJ, submitted (https://ui.adsabs.harvard.edu/abs/2022arXiv220107801J/abstract):

Cosmological Results from the RAISIN Survey: Using Type Ia Supernovae in the Near Infrared as a Novel Path to Measure the Dark Energy Equation of State

Authors: Jones, D. O., Mandel, K. S., Kirshner, R. P., Thorp, S., Challis, P. M., Avelino, A., Brout, D., Burns, C., Foley, R. J., Pan, Y.-C., Scolnic, D. M., Siebert, M. R., Chornock, R., Freedman, W. L., Friedman, A., Frieman, J., Galbany, L., Hsiao, E., Kelsey, L., Marion, G. H., Nichol, R. C., Nugent, P. E., Phillips, M. M., Rest, A., Riess, A. G., Sako, M., Smith, M., Wiseman, P., Wood-Vasey, W. M.

The RAISIN photometry (photometry/) includes optical data from Pan-STARRS (Scolnic et al. 2018, Villar et al. 2020) or DES (Brout et al. 2019; DES et al. in prep) and NIR data from Jones et al. (2022).  CSP photometry is from Krisciunas et al. (2017).  The data are in SNANA format with fluxes ("FLUXCAL") column having a zeropoint of 27.5.  Time of maximum light for each SN is from optical$+$NIR light-curve fitting with SNooPy (Burns et al. 2014).  CMB redshifts and peculiar velocities are computed from SNANA utilities, and Milky Way reddening is from Schlafly & Finkbeiner.  Finally, host galaxy masses are computed by Jones et al. (2022).

The kcor directory includes SNANA input files that define the filter system and the k-corrections used in the SNooPy light-curve fitting procedure.

SN distance measurements, systematic variants, and covariance matrices (distances/) are from the analysis in Jones et al. (2022).  Distances are provided in SNANA's FITRES format, which can be read as an ascii-formatted astropy table.

For any issues or questions, please raise an issue on GitHub and I will address them as soon as I can.
