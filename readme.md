The data_synthesizer - a tool to generate useful data similar to input data given in a csv file.
-

To run the synthesizer with your desired configuration, use the file named "config.json", describing the output you want to generate.
An example config file is provided.
These are the configurable parameters:


* Input File: Path+name of the input data file, that shall be used for data generation, given as string. 
* Output file: Path+name of the file where we want the output to be written to.
* Percentage: A floating point number, which designates the percentage of non-NaN. The maximum percentage of non-numeric types that you want to allow in any column, as float, ranging from 0.0 to 1.0.
entries a column must have to be considered for data generation. 
* n_samples: The number of new lines of data the program should generate for you, gicen as positive integer.
* Features: The headers of the colums of your input file you want to include in the new data as value pairs. Each feature is a key, where the value pair can be either "categorical" and then none type or a "numerical" value and then the appropriate data type (float|int). 


Software versions:
-
See [requirements.txt](https://github.com/dude2033/data_synthesizer/blob/master/requirements.txt).
