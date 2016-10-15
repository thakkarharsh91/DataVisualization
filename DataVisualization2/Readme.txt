README

The zip file uploaded in blackboard contains following files and folders:

1. Social-Media-Mining-master folder - which is the actual web application project which contains all the source code and the web pages.
2. CrawledFiles folder- which contains all the crawled files. The crawling is done with the help of Jsoup library.
3. IndexedFiles folder - which contains all the indexed files. The Indexing is done with the help of Lucene library.
4. Readme file - which contains the detailed instructions on how to execute the web application project.
5. data.xlsx - Provided as part of the assignment which contains the stack overflow posts.

Instructions to run the project:

1. Extract the zip file and place the folder Social-Media-Mining-master which is the actual project in the respective workspace.
2. Configure the apache tomcat server in the workspace. Currently Java version 8 and apache tomcat 8 are use to develop the project.
3. Place the folders CrawledFiles and IndexedFiles and the file data.xlsx in C: drive. This project is developed keeping windows OS as the base OS.
4. Right click on the project and clicks Run As -> Run on server to run the application.

Run Crawling and Indexing separately:

1. Also if the user individually want to perform crawling and indexing on other posts other than the one mentioned in the assignment (data.xlsx), then the same can be performed by running the files WebCrawler.java and WebIndexing.java as java application. 
2. Both of these files have individual main methods so they can run independently as Java application.

Steps to get the desired output when the application is run:

1. Select the post from the dropdown which has values from post1 to post10.
2. Click on submit button. The page will get refresh and top 10 search results will be shown in the text area.
3. Now if one wants to view the results of some other post, then he needs to click the refresh button first which will refresh the page and clear all the contents.
3. There is also a link provided in the web page to explain the process of Crawling and Indexing. Once that link is clicked, the window pop up will open and the user can get the knowledge on both the processes.
