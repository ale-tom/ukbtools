
# Update to version 0.11.0


## Test environments

* local OS X High Sierra 10.13.2, R version 3.5.0 (2018-04-23)
* ubuntu 14.04 on travis-ci (devel and release)
* win-builder (devel and release)


## R CMD check results

#### local macOS High Sierra 10.13.4, R version 3.5.0 (2018-04-23)
Status: OK
R CMD check results
0 errors | 0 warnings | 0 notes
R CMD check succeeded


#### ubuntu 14.04 trusty on travis-ci (devel and release)
R-release
R 3.5.0 (2017-01-27)
Status: OK
Done. Your build exited with 0.

R Under development (unstable) (2018-05-23 r74770)
Status: OK
Done. Your build exited with 0.


#### win-builder (devel and release)
R-release
Status: OK
R version 3.5.0 (2018-04-23)
platform: x86_64-w64-mingw32 (64-bit)

R-devel
Status: 1 NOTE
* R Under development (unstable) (2018-05-20 r74747)
* platform: x86_64-w64-mingw32 (64-bit)


## Downstream dependencies

There are currently no downstream dependencies for this package





***


# Update to version 0.10.1


## Test environments

* local OS X High Sierra 10.13.2, R 3.4.3
* ubuntu 14.04 on travis-ci (devel and release)
* win-builder (devel and release)


## R CMD check results

#### local OS X High Sierra 10.13.2, R 3.4.3 (2017-11-30)
Status: OK
R CMD check results
0 errors | 0 warnings | 0 notes
R CMD check succeeded


#### ubuntu 14.04 on travis-ci (devel and release)
R-release
R 3.4.2 (2017-01-27)
Done. Your build exited with 0.

R Under development (unstable) (2018-01-22 r74151)
Done. Your build exited with 0.


#### win-builder (devel and release)
R-release
Status: 1 NOTE
* using R version 3.4.3 (2017-11-30)
* using platform: x86_64-w64-mingw32 (64-bit)

Possibly mis-spelled words in DESCRIPTION:
  Biobank (3:34, 6:44)
  ICD (7:67)
  UKB (6:97)
  fileset (6:101)

R-devel
Status: OK
* R Under development (unstable) (2018-01-20 r74146)
* using platform: x86_64-w64-mingw32 (64-bit)


## Downstream dependencies

There are currently no downstream dependencies for this package





***


# Update to version 0.10.0


## Test environments

* local OS X High Sierra 10.13.1, R 3.4.2
* ubuntu 14.04 on travis-ci (devel and release)
* win-builder (devel and release)


## R CMD check results

#### local OS X High Sierra 10.13.1, R 3.4.2

Status: OK
R CMD check results
0 errors | 0 warnings | 0 notes
R CMD check succeeded


#### ubuntu 14.04 on travis-ci (devel and release)

R-release
R 3.3.0
Done. Your build exited with 0.

R-devel
Done. Your build exited with 0.


#### win-builder (devel and release)

R-release
Status: 1 NOTE
* R version 3.4.2 (2017-09-28)

Possibly mis-spelled words in DESCRIPTION:
  Biobank (3:34, 6:44)
  ICD (7:67)
  UKB (6:97)
  dataset (6:82)
  fileset (6:101)
  html (6:121)
  metadata (8:22)

R-devel
Status: OK
* using R Under development (unstable) (2017-09-12 r73242)
* using platform: x86_64-w64-mingw32 (64-bit)


## Downstream dependencies

There are currently no downstream dependencies for this package




***

## Example data

I've left a couple of examples to run, e.g., some of the ICD functions that query publicly available data that I've incorporated as queryable datasets. Most functions however rely on a "UKB dataset" created with ukb_df. ukb_df itself requires raw data (files) from a approved UK Biobank study so this is not feasible. The UK Biobank is very sensitive data (primary demographic data, genetic data, etc.). It would not be easy to generate example data for all the variables required, that is representative of the UK Biobank, without making the UK Biobank and it's participants very uncomfortable.




## Test environments

* local OS X El Capitan 10.11.6, R 3.4.0
* win-builder (devel and release)




## R CMD check results

#### local OS X El Capitan 10.11.6, R 3.4.0

Status: OK

R CMD check results
0 errors | 0 warnings | 0 notes



#### win-builder (devel and release)

R-release
* using R version 3.4.0 (2017-04-21)
* using platform: x86_64-w64-mingw32 (64-bit)

R-devel
* using R Under development (unstable) (2017-06-28 r72861)
* using platform: x86_64-w64-mingw32 (64-bit)


Status: 1 NOTE

* checking CRAN incoming feasibility ... NOTE
Maintainer: 'Ken Hanscombe <ken.hanscombe@gmail.com>'

New submission

Possibly mis-spelled words in DESCRIPTION:
  Biobank (3:34, 6:44)
  ICD (7:67)
  UKB (6:97)
  dataset (6:82)
  fileset (6:101)
  html (6:121)
  metadata (8:22)
  
  


## Downstream dependencies

There are currently no downstream dependencies for this package
