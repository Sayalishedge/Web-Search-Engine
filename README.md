# Web-Search-Engine
Web Search Engine Using Hadoop MapReduce 
Final project of C-Dac PG-DBDA course.
This project is a web based search engine where user enters a query and how many results the user expects regarding that query.
The output is top N results(specified by the user) for that query along with their ids.The user then has to specify which id he wants and enter it below from the top N ids ranging from the most similar web page at the top.
When the user enters the id that he finds relevant, the system provides a url link to that query, which when clicked will be open in the default browser of the user.
The url contains the wikipedia page of the user entered query.

The dataset used in this project is multiple wiki text files containing data of words from A to Z.

We have automated our project into 2 shell scripts.
hooray1.sh is responsible for performing indexing.
hooray2.sh is responsible for ranking and url extraction.

The workflow of the project is specified in the    provided.



