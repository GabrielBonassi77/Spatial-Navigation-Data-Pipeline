# Welcome to the Spatial Navigation Data Pipeline

This data pipeline allows users to extract useful motion data from videos in a straightforward manner. In regards to it's application in neuroscience, the velocity threshold algorithm utilized by the data pipeline can calculate the velocity of individual body parts between frames and automatically remove data points that exceed a set velocity threshold. In theory, by removing neural data points at times where motion exceeds the set velocity threshold, it should be possible to increase the signal-to-noise (S/N) ratio of neural data. This is based on the idea that while collecting neural data, intense movements can sometimes result in neural activity that is not relevant to the task at hand. The velocity threshold algorithm is authored by [Gabriel Bonassi](https://www.linkedin.com/in/gabriel-bonassi-6421b5169/) and was inspired by [Dr. Roberto Vincis](https://www.bio.fsu.edu/vincislab/) of Florida State Univeristy.

Note: this data pipeline is meant for analysis of motion data obtained from video via DeepLabCut (DLC). This repository will not explain how to use DLC, so visit https://github.com/DeepLabCut/DeepLabCut to download and learn how to use the library.

To get started please download Anaconda if not already installed.

https://docs.anaconda.com/anaconda/install/windows/ 

From the Anaconda Home Page, click on Jupyter Notebook. You must install it if using Anaconda for the first time.

![This is an image](https://github.com/GabrielBonassi77/Spatial-Navigation-Data-Pipeline/blob/main/Screenshot%202022-05-12%20163219.png)

After opening J
  
