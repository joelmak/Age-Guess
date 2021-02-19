# Age-Guess
Age Guess Codes
## Libraries
#imported libraries on jupyter notebook (if they were not already installed,I installed them onto the environment in anaconda navigaotr): 
#numpy
#pandas 
#seaborn
#matplotlib.pyplot

## Introduction
#Datasets were collected from Age Guess open source data. The purpose of this study is to determine the biological age with the perceived ages of different people around the world. People upload their photos and the gamers will then guess their ages based on those photos. 

## Analysis
#There were 5 datasets in csv format. They were imported onto jupyternote book and displayed. The data was first displayed on summary tables and then later were treated - cleansed, and relevant one segregated. The missing values were checked for and dropped, NaN values were replaced with 0- where applicable. The description of the datasets were also checked to view some basic statistical details, the info of the data - displaying a more concise summary of the data also to see missing values was also viewed. For some dataframe, the columns were extracted.
#For the Data report dataset, the unique comments were extracted and totals were found for each category and later plotted on a bar graph. 
#for data_gamers, a new dataframe was created with some attributes to see the relationship and changes thereof. The total count of guesses and correct guesses were also plotted on line graphs based on ethnicity. The relationship and total counts of how many photos were uploaded were summarized in a table to see the relationship. A correlation matrix was also plotted to see the relationship between the guesses and correct  guesses. The birth country and the and number of photos were also plotted on a summary table to view the relationship between these variables. 

## Results
#There were 12 unique values that were extracted from the data report data set and plotted on a graph. The comment with the highest counts was 'photo deleted by user' with a sum of 706. Next, a strong positive correlation between the guesses and correct guesses. It was also found that the gamers accessed the game from about 109 countries around the world, The countries with the highest guesses were the United States and United kingdom. This is possibly because the game is popular in these regions. The total Guesses were segregated by ehtnicity, with the highest being caucation for both correct and total guesses.
#The game is quite interesting, however, it does not reach a definitive conclusion as an acurate age allocator as people may look different in pictures. Also, the standard deviation from the guesses is usually over and below the actual age, which proves again that it is not entirely accurate to use this method as a age guesser. 

## Credits
The analysis was based in datasets attained from: ageguess.org
The information was analysed from: 
Jones, J.A.B., Nash, U.W., Vieillefont, J. et al. The AgeGuess database, an open online resource on chronological and perceived ages of people aged 5–100. Sci Data 6, 246 (2019). https://doi.org/10.1038/s41597-019-0245-9
