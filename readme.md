The data_synthesizer is a tool to generate usefull data similar to input data given in a csv file.
To run the synthesizer configure a file named "config.csv" detailing the output you want to generate.
An example config file is provided.

Features: The headers of the colums of your input file you want to include in the new data. (string)

Type: Data type of the feature. Currently only categorical and numerical.

Subtype: Subtype of the feature if Type is numerical. Either integer or float.

Percentage: The maximum percentage of non-numeric types that you want to allow in any column. (float between 0.0 and 1.0)

Number of Samples: The number of new lines of data the program should generate for you. (positive integer)

Input File: Path to the input data file. (string)

Output File: path to the file you want to save the new data in. Will be generated if non existend. (string)