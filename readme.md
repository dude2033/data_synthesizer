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

Software versions:
-----
pandas              1.4.2
sdv                 0.15.0
-----
modules imported as dependencies
backcall            0.2.0
colorama            0.4.3
copulas             0.7.0
ctgan               0.5.1
dateutil            2.8.2
debugpy             1.6.0
decorator           5.1.1
dill                0.3.4
entrypoints         0.3
executing           0.8.3
faker               9.9.1
graphviz            0.20
ipykernel           6.13.1
ipython_genutils    0.2.0
ipywidgets          7.7.0
jedi                0.18.1
joblib              1.1.0
llvmlite            0.38.
netifaces           0.10.4
numba               0.55.2
numpy               1.22.4
packaging           21.3
parso               0.8.3
pexpect             4.6.0
pickleshare         0.7.5
prompt_toolkit      3.0.29
psutil              5.9.1
ptyprocess          0.7.0
pure_eval           0.2.2
pyarrow             8.0.0
pydevd              2.8.0
pygments            2.12.0
pyts                0.12.0
pytz                2022.1
rdt                 0.6.4
scipy               1.7.3
sdmetrics           0.5.0
six                 1.14.0
sklearn             1.1.1
stack_data          0.2.0
threadpoolctl       3.1.0
torch               1.11.0+cu102
tornado             6.1
tqdm                4.64.0
traitlets           5.2.2
wcwidth             0.2.5
yaml                5.4.1
zmq                 23.1.0
-----
IPython             8.4.0
jupyter_client      7.3.4
jupyter_core        4.10.0
notebook            6.4.12
-----
Python 3.8.10 (default, Jun 22 2022, 20:18:18) [GCC 9.4.0]
Linux-5.15.0-46-generic-x86_64-with-glibc2.29