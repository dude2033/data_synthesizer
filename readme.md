The data_synthesizer - a tool to generate useful data similar to input data (a single table) given in a csv file.
-


This project presents a Jupyter Notebook for running python code to create a synthetic data file out of a dataset, that has to be translated. 
To open the respective Jupyter Notebook please see the file [data_synthesizer.ipynb](https://github.com/dude2033/data_synthesizer/blob/master/data_synthesizer.ipynb).


To run the synthesizer with your desired configuration, use the file named "config.json", describing the output you want to generate.
An example config file is provided.
These are the configurable parameters:


* Input File: Path+name of the input data file, that shall be used for data generation, given as string. 
* Input Column Separator: Most csv files have a "," separator, however some also use semicolons ";" or tabs "\t" instead. Please then specify with this config parameter.
* Output file: Path+name of the file where we want the output to be written to.
* Percentage: A floating point number, which designates the percentage of non-NaN in input to be taken into account. The maximum percentage of non-numeric types that you want to allow in any column in input, as float, ranging from 0.0 to 1.0.
entries a column must have to be considered for data generation. 
* n_samples: The number of new lines of data the program should generate for you, given as positive integer.
* Features: The headers of the columns of your input file you want to include in the new data as value pairs. Each feature is a key, where the value pair can be either "categorical" and then none type or a "numerical" value and then the appropriate data type (float|int). 


Software versions:
-
See [requirements.txt](https://github.com/dude2033/data_synthesizer/blob/master/requirements.txt).

Examples:
Next to the given [config.json](https://github.com/dude2033/data_synthesizer/blob/master/config.json) that references a glioma dataset [combined.tsv](https://github.com/dude2033/data_synthesizer/blob/master/combined.tsv), collected from cbioportal and used in ["Gashi M, Vuković M, Jekic N, Thalmann S, Holzinger A, Jean-Quartier C, Jeanquartier F. State-of-the-Art Explainability Methods with Focus on Visual Analytics Showcased by Glioma Classification. BioMedInformatics. 2022; 2(1):139-158. https://doi.org/10.3390/biomedinformatics2010009"](https://www.mdpi.com/1455988).
There are also other config possibilties available via [config2967.json](https://github.com/dude2033/data_synthesizer/blob/master/config2967.json) and [config444.json](https://github.com/dude2033/data_synthesizer/blob/master/config444.json).
