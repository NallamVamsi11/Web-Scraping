# Web-Scraping
Web scraping is a technique used to extract data from websites, and one popular application is scraping GitHub topics using Python and BeautifulSoup. GitHub is a platform that hosts millions of repositories and allows users to categorize their projects using topics. By leveraging Python and the BeautifulSoup library, you can automate the process of extracting information from GitHub topic pages.

To begin, you'll need to install the required libraries: BeautifulSoup and requests. You can install them using pip, the package installer for Python. Once installed, import the necessary modules into your Python script.

In this project we extract the information of  top 30 topics(topic name , url ) in github topics section. Then for each topic we extract the details of top 30 repositories in that topic section (repo name , user name , url , no of stars) and save these info in corresponding csv files in our system.
