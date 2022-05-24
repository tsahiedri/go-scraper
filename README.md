
# Go Web Scraper

The following repository contains a web-scraper using Go language and Colly framework. <br /> <br />
The data source for the web-scraper is [j2store](http://j2store.net/demo/index.php/shop), which is a demo online shop site that used as a free template with sample data. <br /> <br />

This web scraper extracts the following data:
* Products names
* Prices
* Image-Url <br />

and outputs the data to a json file (named products.json) in the following format: <br />
<pre>{ <br />
"name": "X", <br />
"price": "$XX.XX", <br />
"imgurl": "XX.png" <br />
}</pre>
