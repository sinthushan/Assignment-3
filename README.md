# Assignment-3
***
### The notebook to run is located in the Starter_Code folder and is called "whale_analysis.ipynb"
### initial CSV files are located in Starter_Code->Resources
### CSV files from google finance extract located in "Resources - Google Sheets" folder
### <span style="color:red"> Please note that all Answers to the questions are written in red font after the code output (this is only tru if opened in jupyter lab doesn't seem to work in github) <span>
***
## Program Desciption

The goal of the notebook is to look at portfolios from 3 different categories: 

1. Whales (investors that have shown to make high and consistant returns)
2. Algo (algrotithmic trading firms)
3. S&P 500

We then compare risckiness and return using standard deviation, Sharpe ratio, and Beta.

We then introduce our own portfolio ade u of 3 to 5 random stocks and see how out metrics hold up against the other three types of portfolios. I chose AAPL, FB and GOOG.

## Dependencies:
1. pandas
2. numpy
3. datetime
4. pathlib

## Notes for TAs:

The metrics for Whales, algo, and S&P 500 portfolios change in the second portion of the assignment when comparing to the personal portfolio becasue the data I gathered was only since 2017 so when I dropped the NAs after combining my portfolio with the rest two years worth of data was dropped (my bad).

When preparing the data extracted from google I skipped the portion which asked us to reset the index and pivot becuase I felt that with the format of the output these steps were unnecessary. Looking at the sample output from the starter code and what i output when I create the data frames I think you can see what I mean (again my bad if I am totaly wrong here):

![My code](Images/mycode.png?raw=true "My Code")
![example code](Images/sampleCode.png?raw=true "Example Code")