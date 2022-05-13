# Welcome to the Spatial Navigation Data Pipeline

This data pipeline allows users to extract useful motion data from videos in a straightforward manner. In regards to it's application in neuroscience, the velocity threshold algorithm utilized by the data pipeline can calculate the velocity of individual body parts between frames and automatically remove data points that exceed a set velocity threshold. In theory, by removing neural data points at times where motion exceeds the set velocity threshold, it should be possible to increase the signal-to-noise (S/N) ratio of neural data. This is based on the idea that while collecting neural data, intense movements can sometimes result in neural activity that is not relevant to the task at hand. The velocity threshold algorithm is authored by [Gabriel Bonassi](https://www.linkedin.com/in/gabriel-bonassi-6421b5169/) and was inspired by [Dr. Roberto Vincis](https://www.bio.fsu.edu/vincislab/) of Florida State Univeristy.

**Note: this data pipeline is meant for the analysis of motion data collected from video(s) with DeepLabCut (DLC), a python based deep neural network library. This repository does not explain how to use DLC, so visit https://github.com/DeepLabCut/DeepLabCut to download and to learn how to use the library. For novice programmers, the DLC GUI is highly recommended.**

## How to Use the Data Pipeline

To get started, the only thing you need to analyze data is the .h5 file that is produced after you analyze a video with your trained DLC network.

Next, download Anaconda if you have not already done so.

https://docs.anaconda.com/anaconda/install/windows/ 

From the Anaconda Home Page, click on Jupyter Notebook. You must install it if using Anaconda for the first time.

![This is an image](https://github.com/GabrielBonassi77/Spatial-Navigation-Data-Pipeline/blob/main/Screenshot%202022-05-12%20163219.png)

Once Anaconda is downloaded, click launch to open Jupyter Notebook. A popup window in your browser should have appeared. Now, upload your .h5 file using the button on the top right corner. Next, upload the SpatialNavigationPipeline.ipynb file by also using the upload button. Then, click on the SpatialNavigationPipeline.ipynb file and navigate to the third code text box. In this code snippet, change the name of the video and DLCscorer variables to match that of your .h5 file that you uploaded. If you just want to demo the pipeline, feel free to use the included .h5 file in this repository. 
  
