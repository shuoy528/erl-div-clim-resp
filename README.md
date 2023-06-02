# erl-div-clim-resp
----------
# Replication code for "Diverging Climate Response of Corn Yield and Carbon Use Efficiency across the U.S."
----------
This repository contains the codes for the economic research paper titled "Diverging Climate Response of Corn Yield and Carbon Use Efficiency across the U.S." by . For any questions or issues, please contact the author of the research paper. Thank you for using these codes!

Last Revision: April 2023.

---------
# How to run the files in this repository? (Pipeline)
---------
The codes are written in Python and JavaScript, and are designed to be run on the Jupyter Notebook and Google Earth Engine code editor. The following are the three main steps to run the codes:

## Step 1: Run Scripts on Google Earth Engine Code Editor
#1. Open the Google Earth Engine code editor (https://code.earthengine.google.com/).
#2. Copy paste the scripts “DownloadWeatherData”, “DownloadNPPData”, and “DownloadGPPData” to the code editor.
#3. Run each script separately by clicking the “Run” button.
#4. Start the tasks by clicking the “Run” buttons in the “Tasks” panel.
#5. These scripts will download the required weather, net primary productivity (NPP), and gross primary productivity (GPP) data from the Google Earth Engine platform.

## Step 2: Download Data from Google Drive
#1. After running the scripts on Google Earth Engine, the generated data will be stored in your Google Drive.
#2. Go to your Google Drive (https://drive.google.com/) and locate the “Data” folder where the generated data is stored.
#3.Download the data from the “Data” folder to your local machine for further analysis. (For replication and illustration purposes, we included the data used to generate the results in the “Data_original” folder available at https://drive.google.com/drive/folders/15NathavIJNCke5W3Hod0wfGLg1c0ksjc?usp=sharing.)

## Step 3: Run Codes in Jupyter Notebook
#1. Open Jupyter Notebook on your local machine.
#2. Run the Jupyter Notebook files in the “Codes” folder. The codes should be executed in the following order: 
- USDANASSData.ipynb: This script downloads county-level yield data from USDA NASS using the Quick Stats API.
- WeatherData.ipynb: This Jupyter Notebook file contains the code for weather data preprocessing and cleaning. It prepares the weather data for the data analyses.
- WeatherVisualization.ipynb: This Jupyter Notebook file contains the code for visualizing the weather data. It generates maps shown in Figure 2.
- Regressions.ipynb: This Jupyter Notebook file contains the code for regressions, including the Random Forest regression and county-level time series regressions, using the cleaned data. It also contains the code for visualizing the results of the data analysis, such as generating plots or maps as shown in Figures 2 and 3.
- MovingWindowReg.ipynb: This Jupyter Notebook file contains the code for moving window regressions, using the cleaned data. It also contains the code for visualizing the results of the data analysis, which generates maps as shown in Figure 4.
#3. Note: Please make sure to follow the dependencies and installation instructions provided in the codes to ensure smooth execution. Please refer to the comments in the code for additional instructions or explanations.
