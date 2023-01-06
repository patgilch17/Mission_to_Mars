# Mission_to_Mars

### Overview
The goal of this Mission to mars project was to learn how to scrape a Web Address for the data you want.  This is an important lesson because when you are handed a project, there may not always be a readily available dataset or the website you want to pull information from may not have an API to handle the process.  Web scraping then is a process that allows us to bridge this gap where we can view the HTML of the website in question and, as long as we understand the structure, pull out necessary information.

For the first portion of our project we scraped the titles and teaser snippits of all the articles from the website [redplanetscience.com](https://redplanetscience.com).  This is a good example of what one might do if they were trying to quickly pull information from reviews of a product.  A useful skill when you are trying to identify public response to your product or find out other the public views your competitors.

The second portion of our project has us working with a table element that displays some generic weather data from the curiosity rover on mars.  To do this we identified the elements (HTML tags) within the table element that contain the data and then have our scrape go through and pull the data portion of these elements.  Finally we performed some analysis to understand the conditions on mars over the course of a year.