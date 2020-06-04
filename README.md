# MUST READ #

THIS DATASET IS ALSO USED IN Car Angle Track Direction Classification (TYPE 1)

** Remember to make a copy of the 'tub_280_20-02-01(Copywithmeta)' folder and rename it as 'tub_280_20-02-01'.

MODEL used for notebook is SavedModel6 NOT SavedModel1

# *All notebooks, saved models and dataset folders must be inside your CWD

# Download Dataset & Saved Model
https://www.kaggle.com/fushenggg/car-angle-direction-classification

*Contains SavedModel6.h5 file to load model (Saves time from training)

Unzip the file and place the 'tub280_copy' folder into your CWD (current working directory) 
Make a copy of the 'tub_280_20-02-01(Copywithmeta)' folder and rename it as 'tub_280_20-02-01'.

Download the ipynb files and place in CWD

Drag the saved model and place in CWD 

# Running the notebook 
1. Check where your CWD is located at

To view your CWD import os os.getcwd()

Mine is 'C:\Users\kansh\Desktop\FYP'

2. Loading of folder from CWD (Changes to make)

Windows uses "\\" & Linux uses "//" for directory path

# There are TWO WAYS to LOAD the folder from directory path
1. filenames = os.listdir('C:\\Users\\kansh\\Desktop\\FYP\\tub280_copy\\tub_280_20-02-01\\'

2. filenames = os.listdir('tub280_copy\\tub_280_20-02-01')

