# SofDes_Midterm_Erhardt1: The Right Stuff
What is the right stuff? The right stuff is a term to represent the qualities possessed by NASA astronauts that make them deemed fit for the job. For our project, we wanted to look at how this concept of the right stuff has evolved over the past sixty years. We accomplished this through a detailed analysis of various astronaut characteristics. We focused most heavily on education, military involvement, and gender. The full report can be found in computationalessay.ipynb.

obtain.py has functions that are are used to obtain the data.

functions.py has functions that are used to clean, manipulate, and visualize the data.

unit_test.py contains the unit tests we made for our data.

Additionally, astronaut-yearbook.zip and astronauts.csv were files obtained by obtain.py, and Test_Data.csv contains test data for our unit tests.

## Requirements Before Running
To run all of the functions you must:
1. Install the kaggle API (https://github.com/Kaggle/kaggle-api) and create an API Token. Place the file in the location ~/.kaggle/kaggle.json. This is used to obtain the data (https://www.kaggle.com/nasa/astronaut-yearbook). Important: Your Kaggle API key will be readable by other users on the system. To fix this, after getting your API key you can run 'chmod 600 /home/softdes/.kaggle/kaggle.json'
2. Install the zipfile module to unzip the data.
3. Install the matplotlib.puplot, pandas, itertools, math, and numpy modules. These are used to create the visualizations.

## Sources

Bennett, Jay. “How the 'Right Stuff' to Be an Astronaut Has Changed over the Years.” Science, National Geographic, 10 Feb. 2021, www.nationalgeographic.com/science/article/how-the-right-stuff-to-be-an-astronaut-changed-over-the-years. 

Kovacs, Gregory TA, and Mark Shadden. "Analysis of age as a factor in NASA astronaut selection and career landmarks." PloS one 12.7 (2017): e0181381.

NASA Astronauts, 1959-Present, Kaggle, 2017, www.kaggle.com/nasa/astronaut-yearbook. 
