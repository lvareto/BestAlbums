# BestAlbums
Data analytics of Rolling Stone magazine's lists of best albums of all time in 2003 and 2020

The BestAlbums project has as objective to analyse the data from the 2003 and 2020 Rolling Stone magazine's lists of the 500 best albums of all time and then to discover data insights related.

## Data collecting from Discogs API
The first part of this project is to build a dataset with some selected atributes from the albums in the lists. So, I did Python script in Jupyter Notebook named 'dataCollecting.ipynb'. In this code I used webscrapping to get the album lists from the Discogs website and then I used the Discogs API to get the albums atributes. Some Python libraries were used mainly the BeautifulSoup to manipulate HTML tags and the python3-discogs-client library to get data from API Discogs.

The dataset result is in the json file named 'bestAlbums.json'. It contains the album title, artist, ranking position, year of the list, genre list, styles list, label and year of the release. As it has the 2003 and the 2020 lists, the dataset has 1.000 rows.

## Data analytics and Data visualization
The next parts of the project are in progress, so it will be posted here asap.

### Disclaim
As I am not a data scientist yet, so maybe the coding need to be improved. So, I'll be grateful if you, Python Master, be patient and help me to get better =)
