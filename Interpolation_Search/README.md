# Interpolation Search

## General 
This directory contains one cpp files (interpolationSearch.cpp) that implements textbook version interpolation search. This program is stand-alone. 
## Requirements and Use

### Textbook Interpolation Search

#### Requirements

In order to compile cpp files a gcc 6 or above is needed

#### Compile

To compile use:

```Shell

g++ interpolationSearch.cpp -o [outputFilename]

```

[outputFilename] must be replaced by the name of the file that will be executed

#### Run

To run Interpolation Search use:

```Shell

./[outputFilename] -p [Path] -d [Dataset] -q [Query] -o [Output] -n [iteration]

```

Argument:
* -p Path of Resource file (e.g.: "./Resource/")  
* -d Name of dataset file (e.g.: "uni01")  
* -q Name of query (e.g.: 10% query name is "10")  
* -o Name of output csv file with time results (e.g.: "interpolationSearchTime.csv")
* -n Number of times to repeat the experiment (Final time is the mean of the times of each iteration) 
