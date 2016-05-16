What is QTrade?
===============
QTrade is a Stock Trading Engine written on top of Flask and MySQL. It utilizes the Yahoo Finance API. A special thanks to github user gurch101 for providing some great code on accessing the Yahoo API. I also have to thank the folks at NASDAQ who compiled NASDAQ, NYSE, and AMEX listings into easy-to-read CSV files, which I have used to populate my SQL server. 

How it works
============
I'm a huge fan of Investopedia. It provides some quality Stock Trading advice and has a really cool stock simulator game. Unfortunately, this stock simulator cannot be accessed programatically, which makes it fairly difficult to test out Algorithmic Trading techniques. QTrade acts as a way for algorithmic traders to practice their algorithms. You can use GET requests to access data related to the ticker that you're interested in and then use this data to trade on that ticker using PUSH commands. Documentation on how to do this will be provided soon. Furthermore, through your account, you will be able to access account and trade information, as well as view the progress on your algorithmically traded portfolio

What's Next?
============
Basically everything. I've done essentially nothing so far. This includes: 
* Downloading MySQL 
* Creating SQLAlchemy Tables for Stocks, Trades, and Accounts
* Creating a Flask server that allows fot GET requests to access all stockdata.py commands and PUT commands to actually make trades (as long as there is money in peoples' accounts)
* Allow for account sign-ups and API key generation
* Allow for Data Visualization of account information via d3.js

