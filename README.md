# Bug-Priority-Prediction
Predicting Bug Priority using Neural Model GPT2. 
This project was undertaken as a project endeavour for SWE795: Intersections between Deep Learning and Software Engineering as hosted by Professor Dr. Kevin Moran on Spring'21 in George Mason University

## Folders:
code - Contains the JuPyter Notebook Code to all the experiments.
output - Contains the outputs to the experiments, some graphs and the classification reports for the Neural models.
data - Contains the data from Long Lived Bug Prediction Project used in the experiments for this project.
The filenames are mostly self-explanatory.

## Replication:
To replicate the results. Please clone the repositories or download the individual JuPyter Notebook.
Run the cells one by one. The default value for 'filename' variable is 'eclipse_bug_report_data.csv'. Change this to 'mozilla_bug_report_data.csv'.
Any other bug report data csv files from Bugzilla is supported by these experiments.

## Package Installation:
Perform the recommended packange installation should you be prompted to: Packages like scikit, numpy, among others. 
Refer to the error texts and use "!pip install" with whatever package-name is missing to run the experiments fully.
List of Packages
numpy
pandas
sklearn
gensim
matplotlib
imblearn
transformers
torch

There are multiple features from within these package that are necessary for the experiments to run fully.
    
## Disclaimer:
GPU usage can run high. Please don't let the experiment break your device.
Devices without GPU are recommended to skip the Neural models experiments part, or only run it with very little data for small number of epochs. 
The notebook contains all the scraps of outputs I had encountered the last time I run the outputs. 
The outputs contain the data I obtained through the experiments.

## Author's Message:
Happy Experimenting. All the best.

Regards,
  Divesh Upreti
