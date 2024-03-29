 # MachineLearning in Forex and Binary Options
 **If you find this useful, you can hire me to help you with your project on https://lucem.dev**
 
 ![machine learning](https://udemy-images.udemy.com/course/750x422/592338_1537_4.jpg)

 ##### please note that this requires a deep knowledge in forex, python and a bit of AWS Machine Learning Service

 ## Usage

 1. clone the project: the main file is main.py(ofcourse). This file manipulates data to produce relevant data for analysis, you can read below for more
 2. download your data: the data in use is from [HistData](http://www.histdata.com/) site
 3. process your data: run main. the input data file is raw.csv and output is data.csv
 4. upload output to AWS for analysis with ML

 ## More
 For machine learning introduction with AWS, watch this video
 [![image](https:\/\/i.ytimg.com\/vi\/TzLuAjhfSrE\/default.jpg)](https://www.youtube.com/watch?v=TzLuAjhfSrE)

 ## Data
 The raw data in csv has the columns:
 1. time/date : EST with no daylight saving
 2. candle open
 3. candle high
 4. candle low
 5. candle close
 6. volume : this is invalid entry for now

 ## Processing
 main.py loops through the data producing numeric values with patterns
 I use one modified indicator (RSX) for trends and an Artificial Neural Network to produce all the values.
 RSX gives the directional momentum on average but plays a role in analysing the various changes in the market over time
 the ANN used processes the data with several hidden layers which produce the final values

 ## Testing
 this project has heavily reliance on AWS services interaction since it is not implemented with any APIs,
 i hope this helps to ease your implementation.

Happy Trading

 
