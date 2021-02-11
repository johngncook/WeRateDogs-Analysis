# WeRateDogs-Analysis
This is a project from Udacity's Data Analyst Nanodegree Course to gather, clean, and analyze twitter data from the twitter handle WeRateDogs. This repository includes all the data used in the analysis plus reports at the end of the analysis. If you only want to see the analysis just browse the WeRateDogs_analysis.ipynb. It is a jupyter notebook file.

### Prerequisites

In order to do this analysis the following libraries were used:

* numpy
* pandas
* seaborn 
* matplotlib
* tweepy

Enter the following into the terminal:
```
pip install numpy
pip install pandas
pip install seaborn
pip install matplotlib
```

### The Data

* twitter-archive-enhanced.csv is the main csv file containing data on the specific WeRateDogs tweets given as the starting data for the project.
* image-predictions.tsv file given by Udacity containing data on neural network predictions of dog breeds based on their post images.
* tweet_json.txt json file containing data that was taken directly from twitter using tweepy in order to get reweets numbers and favorite numbers for the tweets in the twitter-archive-enhanced.csv.
* twitter_archive_master.csv master dataset containing the final product after data cleaning and merging variables from the other files. All set for analysis.


## Author

* **John Cook** - *Initial work* - [johngncook](https://github.com/johngncook)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Thanks to Udacity for giving me the opportunity to work on this project and grow as a data analyst!

