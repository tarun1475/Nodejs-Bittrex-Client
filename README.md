# README #

Implementation of Bittrex Client in Nodejs. 

### What is this package for? ###

This package is for developers who want to integrate Bittrex Exchange apis in their app using  nodejs. All Public & Private Routes have been implemented and tested.

### How do I get set up? ###

* npm i bittrex-js-client
* make sure you have node installed on your machine

### How do i get set up Key & Secret ? ###

Check: https://github.com/tarun1475/Nodejs-Bittrex-Client/blob/master/constants.js

# Examples #



# getMarkets #

```
var bittrex = require('bittrex-js-client');


bittrex.getMarkets();

```

# getCurrencies #

```
var bittrex = require('bittrex-js-client');


bittrex.getCurrencies();

```

# getTicker #

```
var bittrex = require('bittrex-js-client');



// e.g BTC_LTC
bittrex.getTicker(market);

```

# getMarketSummaries #

```
var bittrex = require('bittrex-js-client');


bittrex.getMarketSummaries();

```

# getMarketSummary #

```
var bittrex = require('bittrex-js-client');


bittrex.getMarketSummary(market);

```

# getOrderBook #

```
var bittrex = require('bittrex-js-client');


bittrex.getOrderBook(market, type);

```

# getMarketHistory #

```
var bittrex = require('bittrex-js-client');


bittrex.getMarketHistory(market);

```


### All Market Routes ###

# buyLimit #

```
var bittrex = require('bittrex-js-client');


bittrex.buyLimit(market, quantity, rate);

```

# sellLimit #

```
var bittrex = require('bittrex-js-client');


bittrex.sellLimit(market,quantity,rate);

```

# cancel #

```
var bittrex = require('bittrex-js-client');


bittrex.cancel(uuid);

```

# getOpenOrders #

```
var bittrex = require('bittrex-js-client');


bittrex.getOpenOrders();

```



```
For More info and code repo have a look at : https://github.com/tarun1475/Nodejs-Bittrex-Client

Developer Email: tarunkumargupta14@gmail.com

Future Task: Account apis & Web Sockets.


