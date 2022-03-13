RAISIN Distances and covariances
================================

This directory contains distance measurements and covariances for optical, optical+nir, and nir-only distances.  We separate the files into those used for the H0 measurement (H0/) and those used for the measurement of w (w/).  The low-z sample for measuring w includes three SNe that are used as Cepheid calibrators in the H0 measurement, so peculiar velocity uncertainty is omitted from these SNe in the H0 directory files.  The H0 files also includes the Cepheid calibrator sample and omits peculiar velocity uncertainty for any Cepheid calibrators (including SN 2007A, which is part of the low-z sample for measuring w).

Distance measurements for the baseline method and each systematic variant are given in the FITOPT*FITRES files.  For each systematic uncertainty in Jones et al. 2022, Table 2, we also provide cosmosis input distances (*lcparams_cosmosis.txt) and covariances (*.covmat) in the syst/ directory.  Descriptions of the FITOPT* files and the systematic files are given below.

These distances and covariances include the Cepheid calibrators for H0.  Three SNe, however, are in both the calibrator set and the low-z sample for measuring w

FITOPT Files: 
  name      |  description
  ----------|-------------
  FITOPT000 |  Baseline distances
  FITOPT001 |  MW E(B-V) scaled by 5%
  FITOPT002 |  HST calibration uncertainty
  FITOPT003 |  Peculiar velocity beta parameter shift
  FITOPT004 |  Mass step location shifted to 10.44 dex
  FITOPT005 |  Mass step shifted by its 1-sigma uncertainties
  FITOPT006 |  BayeSN distances (Mandel+20)
  FITOPT007 |  CSP Y-band calibration offsets
  FITOPT008 |  CSP J-band calibration offsets
  FITOPT009 |  CSP H-band calibration offsets
  FITOPT010 |  CSP B-band calibration offsets
  FITOPT011 |  CSP V-band calibration offsets
  FITOPT012 |  CSP g-band calibration offsets
  FITOPT013 |  CSP r-band calibration offsets
  FITOPT014 |  CSP i-band calibration offsets
  FITOPT015 |  PS1 g-band calibration offsets
  FITOPT016 |  PS1 r-band calibration offsets
  FITOPT017 |  PS1 i-band calibration offsets
  FITOPT018 |  PS1 z-band calibration offsets
  FITOPT019 |  DES g-band calibration offsets
  FITOPT020 |  DES r-band calibration offsets
  FITOPT021 |  DES i-band calibration offsets
  FITOPT022 |  DES z-band calibration offsets
  FITOPT023 |  Low-z sBV mean/dispersion shifted by their 1-sigma uncertainties
  FITOPT024 |  global shift of 0.05 in A_V
  FITOPT025 |  Low-z sBV mean/dispersion shifted by their 1-sigma uncertainties
  FITOPT026 |  low-z shift of 0.05 in A_V
  FITOPT027 |  K-correction systematic shift
  FITOPT028 |  shift due to uncertainty in amount of SN flux in templates

Systematic files:
  name      |  description
  ----------|-------------
  all       |  All systematics
  stat      |  Statistical errors only
  biascor   |  Bias correction systematics
  biascorav |  Systematic variants shifting the A_V distribution
  biascorst |  Systematic variants shifting the sBV distribution
  massstep  |  Mass step systematics
  photcal   |  Photometric calibration systematics
  lowzcal   |  Photometric calibration systematics in the low-z (ground-based) data
  hstcal    |  Systematics in photometric calibration of the HST system
  tmpl      |  shift due to uncertainty in amount of SN flux in templates
  pecvel    |  Peculiar velocity beta parameter shift
  mwebv     |  MW E(B-V) scaled by 5%
  lcfitter  |  BayeSN distances (Mandel+20)
  kcor      |  K-correction systematic shift
