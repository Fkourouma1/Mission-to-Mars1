# Mission-to-Mars Overview
In this project, we are helping Robin who is a junior data scientist. She dreams to work for NASA one day. She is thinking of a web-scraping project. Which will help people get the latest news and updates with the click of a button. We will create a web app for someone who wants to keep up with the Mission to Mars. Using the web scraping technique, she can pull data from multiple websites, store it in a database, then present it on one webpage. We would use chrome dev tools to identify HTML components attached to the data we want to scrape. We would also use BeautifulSoup and Splinter to automate the web browser and gather the data we have identified. We would then use Mongo a non-SQL database to store the extracted data. To display the data, we would create a web application using flask. We would use all these tools to identify, scrape, store, and display information from multiple websites that contain information about missions to mars.


### Resources and Tools
- Tools: Splinter, Web-Driver Manager, BeautifulSoup

- Software: Python 3.9.5, Visual Studio Code 1.57.1, Jupyter Notebook 6.3.0

- Database: MongoDB
### HTML and CSS Bootstrap
Components of the Web Scraping App
Python script to perform the scraping
HTML Index page to display results
Flask App that connects the Python script to HTML and MongoDB in order to display the results

### Deliverables
- We use the Chrome Developer tools to visit the NASA News website and identify the HTML tags that contains the information to scrape

- We automate the Chrome browser using Splinter to visit the URL.

- we use BeautifulSoup to parse the HTML of the page.

- We scrape all appropriate HTML tags for news title and article.

- Then, we visit space images website and identify the HTML tags that contains the information to scrape.

- We automate the browser using Splinter and use BeautifulSoup to scrape the Mars featured image.

- Next, we use Splinter and BeautifulSoup to visit the galaxy facts website to scrape mars facts.

- We parse the scraped data to a dataframe and then convert to HTML table.

- We visit the mars hemisphers website and scrape full resolution images of all 4 mars hemispheres.

- In a python script, we store all the scraped data in MongoDB.

- We have the webpage with mobile-response.

- Finally, we have two additional Bootstrap 3 components are used to style the webpage.
