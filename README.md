# CRYPTOBYTES
# Description
A Digital Currency based Android Application,  which displays market prices of all the Crypto currencies.
# Features
This Application helps users get to know about various Digital coin(cryptos) values their rise and drop of prices very often.
User can check out the latest news of Crypto from all over the world.

# Api Used:
- ### Coin Market Cap 
    - to get list of all the Cryptos ( https://pro-api.coinmarketcap.com/v1/cryptocurrency/listings/latest )
    - to get details of a particular crypto using its symbol ( https://pro-api.coinmarketcap.com/v1/cryptocurrency/info?symbol=btc )
- ### CryptoCompare
    -to get news related to cryptos ( https://min-api.cryptocompare.com/data/news/ )

# Technology Used:
- It is built using Java Language.
- ### MVVM Architecture
    - Model — View — ViewModel (MVVM) is the industry-recognized software architecture pattern that overcomes all drawbacks of MVP and MVC design patterns. MVVM suggests separating the data presentation logic(Views or UI) from the core business logic part of the application.
    - The separate code layers of MVVM are:
        - Model: This layer is responsible for the abstraction of the data sources. Model and ViewModel work together to get and save the data.
        - View: The purpose of this layer is to inform the ViewModel about the user’s action. This layer observes the ViewModel and does not contain any kind of application logic.
        - ViewModel: It exposes those data streams which are relevant to the View. Moreover, it serve as a link between the Model and the View.
MVVM (Model View ViewModel) Architecture Pattern in Android

- ### Libraries for fetching data from Apis

 
