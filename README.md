# project1
README:

In this repository, we analyze the top 1,000 gross movies of all time in different areas.

Overview:
First, we get a dataset of the top 16,000 gross movies of all time from a kaggle dataset that appears to go up to around 2019 or 2020. From there, we create a dataframe from the Kaggle csv. We then split the csv DataFrame into the top and bottom 1,000 lifetime grossing movies (This is for the OMDb API since it can only handle 1,000 requests a day). We then use this top 1,000 movies dataframe and add more information on them using the OMDb API database. From there we clean up the DataFrame we have created with the extra information and create visualizations from them such as Studio information, Box office information, Release Date, etc.

Kaggle dataset:
https://www.kaggle.com/datasets/thedevastator/hollywood-movies-domestic-lifetime-gross-and-ran
OMDb API:
https://www.omdbapi.com/

If doing API Requests, you must put in your own key, gitignore wasn't set up properly :)

Collaborators:
Khyati: thakorekp
Jonathan: jkoo23