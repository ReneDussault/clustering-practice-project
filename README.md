### Music Genre Analysis and Recommendation
This project aims to analyze music genres and provide song recommendations based on user activities such as studying,  
training, or any other activity. It utilizes Spotify's API to gather data on different genres and their associated songs.

#### Project Overview
The project performs the following steps:  
Collects data on various music genres using the Spotify API.  
Extracts audio features of songs within each genre, including energy, instrumentalness, and speechiness.  
Uses K-Means clustering algorithm to group songs into clusters based on their audio features.  
Explores the data.  
Visualizes the clusters in a 3D scatter plot to observe patterns and relationships between genres. (see below)  
Provides song recommendations based on user input activity (study, gym, or anything).  

#### How to Use
To run this project, follow these steps:  
Install the required libraries and dependencies mentioned in the requirements.txt file.  
Create a secret.json file and populate it with your Spotify API credentials (client ID and secret).  
Run the muzziq.ipynb notebook.  
Follow the prompts and input your activity (study, gym, or anything) and the number of songs for your playlist.  
The program will generate a playlist of songs based on your activity and display them.  

#### Results
The project analyzes music genres and clusters songs based on their audio features.  
It provides insights into the distribution of genres within each cluster and displays the average audio feature values for each cluster.  
Additionally, it recommends songs based on user input activity, helping users create personalized playlists for their desired activities.

#### Note
This project is intended for demonstration purposes and showcases the use of Spotify's API and machine learning techniques for music analysis and recommendation.
Please note that this project requires valid Spotify API credentials to access the necessary data.  
Make sure to obtain and include your credentials in the secret.json file before running the code.

##### This README.md file is intended to provide a high-level overview of the project to non-technical individuals, such as recruiters.  
##### For more detailed information and code documentation, please refer to the code files and comments within them. 

here's a 3dplot showing the clustering
![alt text](https://github.com/ReneDussault/clustering-practice-project/blob/main/3dplot.png)
