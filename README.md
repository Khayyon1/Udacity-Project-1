# Write a Data Science Blog Post

## Business Understanding
* Objective of the project: <br> 
Asking questions of interests that arise from the use of the StackOverflow Developer data from 2019 to 2021

* What is the expected effect of the project? What are the success criteria for the project?<br>
The anticipated payoff is just more knowledge about the most commonly used technologies by developers. If the technolgies vary for open-source contributors and less frequent open-source contributors. If this trend changes over time as well. The success criteria is seeing the trends honestly 

## Data Understanding
* Where does the data come from? What are the data sources?<br>
  The data come from StackOverflow, which is a forum used for developers to share information. Post questions and answers based info. posted by users of the platform. It is a trusted sources and seen as a lifeline for many developers of various walks of life. The data sources are surveys from various years taken by developers.
  
* How can we best describe the data at a high level? What is the metadata of our datasets?<br>
 The data being used is StackOverflow survey data that was taken by developers who use and are active on the platform. This has entries recording salary, education level, location, technologies used (databases used, platforms used, languages used, etc), Mental Health, Employment Type (i.e. Full-Time, Part-Time, Student, Unemployed, etc). This can be used to answer some questions in regard to developers based on these results.
 
* How is our data quality?<br>
  The data set between the years have some similarities, like languages worked with, ethnicity, salary and etc. But their were columns that had several NaN, another interesting thing that occurred was the different schemas and columns that appeared between the survey for different years. This did not affect the analysis though because the nature of the questions were geared towards specific things like language and etc between different groups (i.e. open-source contributers, etc)

## Data Preparation
* Did we select the right data?<br>
  Yes, the StackOverflow survey data is the right data for gaining general knowledge about programmers, technologies they use and prefer to work with, contributions to open-source projects and etc.
  
* Do we need to generate new data?<br>
  No, that would invalid the answers that are given from the survey data. The data in the survey is sufficient to answer the questions of interest. Even though no data is generated, it is important to note that their were rows that omitted based on the criteria that was being searched on. I did not attempt to imputed the data or create any categorial data because it would bias the results from the survey so I thought it would be best to ignore any rows with NaN instead of imputing them. 
  
* Do we need to derive new attributes?
  Yes, but it was only one, the Year attribute was added to different between the different survey results. This is not needed, just added for convienience

## Modeling
 The questions asked were able to be answered with only inferential statistics. So no modeling took place for this project. 

## Evaluation
Likewise, no model evaluation was needed for the questions asked for this project.

## Deployment
N/A

# Summary
  between 2019 - 2021, developers seem to really be fond of 
  * Javascript
  * HTML/CSS
  * SQL
  * Python
  
  Developers who contributed more frequently to open-source projects desired to use
  technologies like Node.js, Tensorflow and NET Core. Developers who never contribute to open-source projects desired similar tools
  
  # Next Steps 
  I could add more survey data from previous years to get a better idea of the changing trend in desired technologies. Currently this notebook only uses 2019 - 2021, which is a small timeframe to be drawing any big conclusions from. Maybe after increasing the amount of time from 2019 - 2021 to maybe 2010 - 2021 (i.e. a decade of data) then maybe this can be used to create a model that can guess the trend for the next year.

# Libraries 
* Numpy
* Matplotlib
* Pandas

# Files
* <b><em>data/</b></em> - directory containing all the csv files used throughout the notebook in the repository.
* <b><em>README.md/</b></em> - currently reading it 
* <b><em>stackoverflow_2021.ipynb/</b></em> - interactive python notebook that is used to explore the data in the data directory
