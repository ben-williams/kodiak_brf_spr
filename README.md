# kodiak_brf_spr

General structure is:

scott reproduces the excel spreadsheet - basically a familiarization and training ground

R has 3 files
 - helper
 - vonb
 - brf_spr
 
 Run the vonb.R file first - it generates von Bertalanffy parameters for male and female fish and stores the output in the output folder
 The brf_spr.R file will estimate the current selectivity, M, F, and SPR for a pooled dataset (e.g., all years are bunched together).
 Needs a bit of work to finsh off determining what the F level should be in order to meet a prescribed SPR input.
  - Jane is tasked with it, go Jane!
 
The TMB folder is all C++ code - play in there at your own peril!
