# eBay clone in Java EE

### Class Project for CS144 Web Applications

Main repo for ebay clone with links to all of the separate repos that are used to make the ebay clone web application.

https://github.com/DarinM223/ebay-clone-data-parser - Contains the relational schema and a Java XML Parser that parses xml files containing eBay data and writes all of the data to the MySQL database.

https://github.com/DarinM223/ebay-clone-indexer - Generates Lucene search indexes for the relational schema

https://github.com/DarinM223/ebay-clone-searcher - Apache Axis2 SOAP Web service that allows for basic keyword search, spatial search through a rectangular region, and xml data retrieval for an item given an item id.

https://github.com/DarinM223/ebay-clone-web-app - Servlet and JSP web application that has a search page with a custom dropdown control using Google Suggest API for autocomplete and pagination for the search results and an item description page with Google Maps integration for location. There are also pages that allow a user to securely enter their credit card and "checkout" an item (the actual paying mechanism or credit card validation is not implemented yet)

![Search Page](http://i.imgur.com/k4pIo6K.png)
![Search Results](http://i.imgur.com/ulyf9dj.png)
![Search Results 2](http://i.imgur.com/jh1cjd2.png)
![Item Result](http://i.imgur.com/o2nEvZF.png)
![Item Result 2](http://i.imgur.com/6RhoRpg.png)
![Item Checkout](http://i.imgur.com/vNeEAWG.png)
![Item Confirmation](http://i.imgur.com/7Y8Vcdr.png)
