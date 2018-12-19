# detector_mw

Requeriments:
-Python
-Database of API Calls for both benign files and malware
-Tensorflow


This work is a neural network made to optimize the detection of malwares by classifiers.

It is an Autoencoder, made using Tensorflow and trained to "clean" Windows API calls from executable files.

The csv files contain API Calls made by executables, used for training and testing.

The database of API Calls for benign files is provided in this repository.

The database of API Calls for malware must be found elsewhere, we won't provide it but you can finding them on this link: 
http://ocslab.hksecurity.net/apimds-dataset

Results are on the "TCC" Jupyter Notebook.

I sincerely hope you find it of use.
