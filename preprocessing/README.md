# Word Frequency

## Objective
Usually facilty names and types are written together in the 'facility name' column in a health facility table. For example, "Makala Health Centre". "Makala" is the facility name and "Health Centre" is the type of facility. We need to separate facility name and facility type and put them into two different columns. In order to do that we need to know which words refer to the type of a facility.

## Process
This is a python notebook that runs on google cloud. A python notebook consists of cells that include python scripts. Each cell can be run individually. In order to run a cell, first click/hover on the cell. After the click, you should see an arrow at the left side of the cell. Click on the arrow to run the cell. The cells need to be run top to bottom.
This work consists of four steps.

#### Step 1:
* Create a word frequency table: A word frequency table will be generated after you run this notebook properly. The word frequency table contains words and how many times they are repeated in a dataset.
#### Step 2:
* Go through each word in the word frequency table: Open the word frequency table and keep only the words that refer to a facility type such as Centre, Clinic, Hospital, Health, HC, DISP, PHC .... Basically, you should delete all the words that refer to a facility name.
#### Step 3:
* Repeat steps 1 and 2 for each health facility dataset you have explored in previous landscaping exercises
#### Step 4:
* Combine all the word frequency tables that you created for each health facility dataset into one excel file. Upload that file to your country's Health Facilities dataset folder in the google drive.
