# Binary Search

## Branchfree Binary Search

### Compile

To compile use:

```Shell

g++ branchfreeBS.cpp -o [outputFilename]

```

[outputFilename] must be replaced by the name of the file that will be executed

### Run

To run Branchfree Binary Search use:

```Shell

./[outputFilename] -p [Path] -d [Dataset] -q [Query] -o [Output] -n [iteration]

```

Argument:
* -p Path of Resource file (e.g.: "./Resource/")  
* -d Name of dataset file (e.g.: "uni01")  
* -q Name of query (e.g.: 10% query name is "10")  
* -o Name of output csv file with time results (e.g.: "branchfreeBSTime.csv")
* -n Number of times to repeat the experiment (Final time is the mean of the times of each iteration) 

## Eytzeinger Layout Binary Search

### Compile

To compile use:

```Shell

g++ eytzBS.cpp -o [outputFilename]

```

[outputFilename] must be replaced by the name of the file that will be executed

### Run

To run Eitzeinger Binary Search use:

```Shell

./[outputFilename] -p [Path] -d [Dataset] -q [Query] -o [Output] -n [iteration]

```

Argument:
* -p Path of Resource file (e.g.: "./Resource/")  
* -d Name of dataset file (e.g.: "uni01")  
* -q Name of query (e.g.: 10% query name is "10")  
* -o Name of output csv file with time results (e.g.: "eytzBSTime.csv")
* -n Number of times to repeat the experiment (Final time is the mean of the times of each iteration) 