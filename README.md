# Mooviz
An Information Visualization for Movie Data

*Designed by Karan Achtani, Pravan Kalaga, & David Le*
## The Purpose
We are interested in displaying data regarding box office sales movies of different genres make over time to see if there are any trends in the success of a movie with its genre and the date it was released.

## The Data
We collected data from [The Numbers](http://www.the-numbers.com/movies/#tab=year)
which contained data regarding the release date, title, genre, production budget, and domestic box office sales, and the data is located under data/data.csv. Many of the files had null or blank values for the last two values, so we filtered them out.

## The Visualization
We're visualizing this data through an interactive stacked stream graph using [Will Turman's API](http://bl.ocks.org/WillTurman/4631136) from bl.ocks.org using d3.js, javascript, jQuery, HTML, and CSS.
