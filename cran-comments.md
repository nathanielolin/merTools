## Test environments
* local Windows 7 install, R 3.2.3
* ubuntu 12.04 (on travis-ci), R devel
* win-builder (devel and release)

## R CMD check results
There were no ERRORs or WARNINGs or NOTEs

* Used utils::globalVariables(c(".shinyMerPar", "sig", "sigma")) to fix notes
about unexported objects.
* Used utils::globalVariables(c("term", "estimate", "std.error")) to fix notes 
about unexported objects in `modelFixedEff` function

## Downstream dependencies
There are currently no downstream dependencies. 
