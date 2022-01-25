# Crypto_Price_To_Excel

Get Crypto prices with python without an api key

Coingecko offers an API which don't require any api key and it is free for more details please visit
https://www.coingecko.com/

About the script -->
I wanted to track my crypto prices daily on excel so i can calculate my daily gains/losses. I was facing problems to update it frequently.
So i used python programming and coin gecko api to solve my problem.
This program only fetches coin prices you can do more and try to do various experiments on it as per your requirements and for that visit their official site.
I have implemented in classes and object (OOPS) method but you can also do it by using functional method

Modules used -->
1) requests (for https request and data mining)
2) json (To read json file)
3) openpyxl (to update in excel)
4) datetime (to update date in excel)

This script contains 3 functions

1) getCoinPrice(self, crypto_id, fiat_currency)
This function takes a crypto_id which you need to find on coingecko website
How to find it? --> Well just search for a coin and look for (API id) in info at right side copy that an paste it

You need to include fiat currency in capital or lower (eg--> "INR", "USD", etc.)
This will return a coin price 

2) getMultiplePrices(self, crypto_list, fiat_currency) 
This fuction takes a list of crypto_ids. please refer code and fiat_currency as mention above
This function will return a list of prices in the given fiat_currency parameter format

3) transferToExcel(self, prices_list)
Use this after getting prices list.
This will trasfer data to the excel file.
You can create a new workbook or use an existing workbook but do not forget to mention file location
You can use it as per your convenience I will mention all websites and youtube video tutorial and reference links.

Links -->
1) https://www.coingecko.com/en/api (api link)
2) https://docs.python-requests.org/en/latest/ (requests module documentation)
3) https://openpyxl.readthedocs.io/en/stable/ (openpyxl module documentation)
4) https://www.youtube.com/watch?v=7YS6YDQKFh0 (python excel tutorial)
5) https://www.youtube.com/watch?v=p71SWzjeqtk (Api tutorial)
6) https://www.youtube.com/watch?v=ukwQ9pHyCMg (coingecko api tutorial)

You can also get various crypto information such as coin market cap, inventors, etc. but i have focused mainly on prices in INR.
