This is a straightforward Python project that demonstrates the integration of Scrapy for web scraping and crawling, as well as Flask for micro web development using the Werkzeug framework. 
The project is organized into two separate subprojects within their respective folders.

In the initial phase, the project utilizes Scrapy to extract data from the Internet Movie Database (IMDb) for specific movies of interest. 
The extracted information is then persistently stored in a MongoDB database. 
Since a movie can be effectively represented as a document, MongoDB was chosen as the suitable database for this use case.

The second subproject involves the creation of a web application responsible for presenting the gathered IMDb data in a user-friendly manner.
