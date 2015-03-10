# eBay clone in Java EE

Main repo for ebay clone with links to all of the separate repos that are used to make the ebay clone web application.

https://github.com/DarinM223/ebay-clone-data-parser - Contains the relational schema and a Java XML Parser that parses xml files containing eBay data and writes all of the data to the MySQL database.

https://github.com/DarinM223/ebay-clone-indexer - Generates Lucene search indexes for the relational schema

https://github.com/DarinM223/ebay-clone-searcher - Apache Axis2 SOAP Web service that allows for basic keyword search, spatial search through a rectangular region, and xml data retrieval for an item given an item id.

https://github.com/DarinM223/ebay-clone-web-app - Servlet and JSP web application that has a search page with Google Suggest text autocomplete and pagination for the search results and an item description page with Google Maps integration for location.

Still have to do:

 * Enable secure transactions
 * Add pages to allow a user to pay for an item
