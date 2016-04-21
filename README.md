# DataWorldBank
Sample application made with Jquery Mobile
Direct fork from https://github.com/ismailmu/DataWorldBank

## Original Readme
Data World Bank Mobile Using Jquery Mobile & Apache Cordova

get country :

json :
http://api.worldbank.org/countries?format=json

jsonp :
http://api.worldbank.org/countries?format=jsonP&prefix=Getdata

get topics :
http://api.worldbank.org/topics/

Indicators :

1.AG.LND.FRST.ZS --> Forest area (% of land area)

2.AG.LND.AGRI.ZS --> Agricultural land (% of land area)

3.EN.ATM.CO2E.PC --> CO2 emissions (metric tons per capita)

4.NY.GDP.MKTP.KD.ZG --> GDP Growth (annual %)

5.SP.POP.TOTL --> population, total

Source API :

http://api.worldbank.org/

Example :

http://api.worldbank.org/countries/br/indicators/AG.LND.FRST.ZS?date=2000:2301

br-> brasil
date from 2000
date to 2301

http://api.worldbank.org/countries/all/indicators/AG.LND.FRST.ZS?date=2000:2301

all --> all country

page – utility parameter for paging through a large result-set. Indicates the page number requested from the recordset.
> http://api.worldbank.org/countries/all/indicators/SP.POP.TOTL?page=2

per_page – number of results per page, for pagination of the result-set. Default setting is 50
> http://api.worldbank.org/countries/all/indicators/SP.POP.TOTL?per_page=25
