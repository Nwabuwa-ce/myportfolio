## Introduction
Hi my name is Chukwudum Nwabuwa and I am a Data Scientist.
I have acquired a couple of certifications in Data Science and Machine Learning
and I look forward to putting my skills to good use in real work situations.
I just began putting together my portfolio in a simple way 
to catch the eye of recruiters in the field of data science/analysis

# Basic Analysis of Twitter Stock

I downloaded the Twitter stock market dataset in csv format, from Kaggle.com, 
then I read the csv data into a Pandas dataframe in a Jupyter Notebook,
and set the "Date" column to become the Index.

### Date as Index
![image](https://github.com/Nwabuwa-ce/myportfolio/assets/99978799/a176579e-aad2-4a68-8617-a0eca13107bb)

After setting Date as Index, I removed any null values present in the dataset, 
also using the describe() method to check the overview of Dataset statistics.
Then I plotted a graph of Adj Close vs Date, and I observed that there is a drop in price below $20 between 
the period of late 2015 and late 2017, and in 2021 the price rises to over $70.

### Adj Close on Date
![image](https://github.com/Nwabuwa-ce/myportfolio/assets/99978799/2bede41a-a055-4b64-9177-2c408709e5fc)

Thereafter, I plotted a graph of Volume vs Date, and observed that there are two noticeable spikes
in the graph, sometime in 2016 and in early 2022.

### Volume on Date
![image](https://github.com/Nwabuwa-ce/myportfolio/assets/99978799/d3e15449-db88-4b2e-8c0b-77e22f68d63a)

Lastly I plotted a graph of 50-day moving average, which 
is a technical indicator that stock traders use in guiding their trading decisions.

### 50 Day Moving Average
![image](https://github.com/Nwabuwa-ce/myportfolio/assets/99978799/461991b9-0003-489e-9b5f-2a6d6e83bfd5)

<a href ="https://github.com/Nwabuwa-ce/twitterstock/blob/main/Twitter%20X%20Project.ipynb">View Project on GitHub</a> 

The underlying causes of the phenomena observed in the graphs, 
can be put in better perspective when you consider the economic and political 
circumstances surrounding the given periods. These "underlying causes" however,
are beyond the scope of this project.



# Canada Immigration Analysis
This is an analysis of Canada's Immigration data between the years 1980 - 2013. The dataset was sourced 
from the UN data repository in csv format before it was read into a pandas dataframe. 
In my exploratory data analysis, I set the Country column as Index, checked the .shape() and .info() 
and .describe() of the dataset, and also confirmed there were no null values.

### Dataset with Country column set as Index
![image](https://github.com/Nwabuwa-ce/myportfolio/assets/99978799/5840e9c8-45d4-4410-a495-f092fda1d419)

You can see from the pie chart below, that the Asian continent is by far the largest immigrant group to Canada 
in that time period accounting for over 50% of all immigrants while Europe comes in second with 22%.

### Immigration to Canada by continent
![image](https://github.com/Nwabuwa-ce/myportfolio/assets/99978799/3cbc0617-4c7d-47c6-b0fc-a988f6370050)

In the Area plot below you can see the top 5 immigrant nations to Canada within the given time frame 
namely, India, China, UK, Philippines and Pakistan. 

### Immigration trend of top 5 countries (1980-2013)
![image](https://github.com/Nwabuwa-ce/myportfolio/assets/99978799/e5e579a6-ddf2-477e-866f-355077020a57)

Lastly, you see the bar chart below of Nigerian immigrants to Canada within the given time period,
and how the numbers have spiked in the last few years of the time period.

### Nigerian immigrants to Canada (1980-2013)
![image](https://github.com/Nwabuwa-ce/myportfolio/assets/99978799/66cc00bf-5cd4-4479-b2dd-addac1af6384)

<a href ="https://github.com/Nwabuwa-ce/Canada-Immigration/blob/main/Canada%20Immigration.ipynb">View Project on GitHub</a>

The immigration data to Canada within the years 1980 - 2013 shows that most countries had an upward trend in
immigrant numbers, except for a few countries in Oceania where the trend did not apply.


### Appreciation

Thank you for looking through my simple page! I hope to keep learning and upskilling,
and updating my projects on this platform, as I complete them. 
Thank you once again for believing in me!
