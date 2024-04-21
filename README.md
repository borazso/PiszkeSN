# PiszkesSN

"Ejecta masses in Type Ia Supernovae -- Implications for the Progenitor and the Explosion Scenario" by Bora et al.

The file "MLCS2k2_results.dat" file contains the best-fit MLCS2k2 parameters if the supernovae.
  Redshift: the redshift of the host galaxy
  T0: the time of maximum in the Johnson-Cousins B filter (MJD)
  RV: reddening law used (?)
  AVgal: the reddening of the Milky Way
  AVhost: the fitted reddening values of the host galaxy for the SN
  Mu0: the distance modulus used for the fitting (fixed to the fitted SALT3 value)
  Delta: the fitted MLCS2k2 Delta value
  ChiSqr: the final chi square value of the best fit 

The file "ZTF_points.dat" contains the SDSS g and r magnitudes of the public ZTF data points that were used to extend our lightcurves.

The file "classification.dat" contains the determined Stritzinger and Wang classes for the sample SNe.

The file "maximum_colors.dat" contains the reddening corrected (B-V) colors of the SNe at the time of B maximum.

The "SALT3" folder contains the plots of the best SALT3 fits for our sample. The "SALT3_bestfit_parameters.dat" file lists the best fit parameters for each SNe.
  z: redshift
  t0: the time of maximum in the Johnson-Cousins B filter (MJD)
  x0: the best-fit SALT3 x0 parameter
  x1: the best-fit SALT3 x1 parameter
  c: the best-fit SALT3 c parameter
  mB: the apparent B magnitude of the SN at the time of maximum

The "Minim" folder contains the plots of the best Minim fits for our sample.

The "LCs" folder contains the plots and the data of the observed BVgriz magnitudes for each SN in our sample. The columns of the "*_BVgriz_mag.dat" files are:
  1: MJD
  2: B mag
  3: B mag error
  4: V mag
  5: V mag error
  6: g mag
  7: g mag error
  8: r mag
  9: r mag error
  10: i mag
  11: i mag error
  12: z mag
  13: z mag error
