# College: Racism - Before and After George Floyd

### Scraping
The process of extracting data from a website to retrieve its content. The received input is in HTML format. The tags are cleaned using stopwords and the required segment is saved for further use, usually in a csv format. This is a commonly used technique, the first to do after installing and importing all the necessary packages. I have chosen an article by FSU – Florida State University, to scrape data forgetting the names and coordinates of the capitals of all the states of USA. The scraped data is cleaned, numbers manipulated and allocated into three lists - latitudes, longitudes, and city names
### Sentiment Analysis
The process of interpreting and categorizing the emotion or sentiment conveyed by the speaker in subjective data. Twitter sentiment analysis is for doing the same process, but in a much larger scale with hundreds of thousands of users spread across the country. The centrepiece of this project, the sentiment analysis takes 250 randomly selected tweets per query word given during the call per coordinate points passed and analyses them to give an output whether it is positive, negative, or neutral. All these data are compiled and passed to the next section of the program.
### CSV Write
“Comma separated value” files are commonly used to transfer or exchange data between applications owing to its wide acceptance. It can be viewed in a tabular form and more importantly, it is editable, making the storing of values extremely easy for programs. For my project, the only part to involve this section, is for saving the calculated sentiment values to the corresponding city names and their coordinates. After receiving the calculated value, it will be written into a CSV file and will be called for plotting the chart, later in the program. 
### Display
This segment focuses on showing the calculated values as a visual representation to the viewer. Chart-studio is a great tool in python (and stand-alone) for displaying data in a visual manner using graphs and charts. Here, the saved CSV files contain the name of the city, the location coordinates (rounded off to two decimal places), and the sentiment value (positive and negative in different files) of that query, from that location. From these, the chart-studio tools take the coordinates from all the rows and plot it on the world map (scope = North America). After that, the sentiment values, in terms of percentages, are taken and a circle is plotted on those locations with the radius representing the value 
### Outputs
![Allen1](https://github.com/allenalvin333/CollegeP4/blob/master/Images/1.png)
![Allen2](https://github.com/allenalvin333/CollegeP4/blob/master/Images/2.png)
![Allen3](https://github.com/allenalvin333/CollegeP4/blob/master/Images/3.png)
![Allen4](https://github.com/allenalvin333/CollegeP4/blob/master/Images/4.png)
  
<br/>
  
# Author

#### [``Allen Ben Philipose``](https://allen.iykk.in/) - 18BIS0043
