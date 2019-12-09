# bitcoin-monitor

*Scripting exercise for monitoring bitcoin price for Mobile Software Development*

### Description:

With our bitcoin monitor, the current bitcoin price is queried regularly, evaluated and stored in a local database. Subsequently, you have the option of using a script to make a database query to get back the bitcoin prices for a specific time interval.

- **API ** - With the help of an API call we get the current bitcoin price in a certain currency back from a bitcoin website. This return has to be evaluated by regex to get only a certain amount of data, because the website returns way too much.  The price and date must then be extracted from the string. The revised data is then stored in a local database for later use.
- **Database** - In a local database of MySQL the current bitcoin prices are stored in a table.
  There will be the following columns:
  - id
  - date
  - during 
  - price
  - currency
- **Script**





### To-do:

- [ ] API access
