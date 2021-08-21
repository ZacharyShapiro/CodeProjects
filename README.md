# CodeProjects

Stock Script : 

For my first attempt at Object-Oriented programming, I've created a python script that pulls some snapshot data about S&P 500 stocks from the IEX Cloud Console API, and then stores that data in my SQL Database.

I chose to do this in an object-oriented fashion so it would be extendable - in future, I can create more sub-classes that inherit the API Key and request formation & SQL query formation from the main class.

For example, if I wanted to store rolling monthly data on stocks, updated daily, I could create a sub-class fetching monthly averages from the API, and create an SQL table within my Stock database to store output.

Market Performance :

Created a database in SQLite in order to store a set of performance results about ~8000 different securities over a period of 12 years. The code I uploaded to github has various functions intended to aide the user in interacting with the dataset, whether to pull certain requests or to convert between python & excel time conventions. 
