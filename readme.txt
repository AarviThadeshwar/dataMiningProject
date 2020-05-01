CSCI 6443: Data Mining
Mining Data from Spotify using Python
Aarvi Thadeshwar and Mahpara Nuzhat

Project can be found at https://github.com/AarviThadeshwar/dataMiningProject.

src contains Jupyter notebooks for all steps.
- Data extraction: extracting data from Spotify using the Spotipy API
- Data preprocessing: cleaning data by removing duplicates and modifying attributes
- Data exploration: using analytics and visualizations to draw conclusions about data
- Data mining: using logistic regression, k nearest neighbour and decision tree to classify data

data contains the datasets used for Australia, Japan, UK and USA over 2011- 2019.

To execute the code:
- Run 'jupyter notebook' or 'jupyter lab' in your Terminal window.
- Ensure the skikitlearn, matplotlib, pandas, seaborn and numpy libraries are installed.
- Open the path where your file is saved.
- Enter the client id and secret key for your Spotify Developer account.
- Change the read_csv path to include /data/filename.csv