# Reporter Token

 name = "Reporter Token"
 symbol = "NEWS"
 decimals = 18

maxTokens = 60.000.000 
tokensForSale = 36.000.000


Opening time:
 
   endTimestamp = 1529074800;   // (GMT): 2018. June 15., Friday 15:00:00

## Presale and Public Sale (fallback function)

* min purchase 0.0001 ether
* max purchase 1000  ether;
* no pre-authorised 

## Private Sale (placeTokens)

* by CS user
* tokens minted on demand before or while sale is active.
* call `placeTokens()` function

## Authorisation

* by CS user or owner
* can approve or block
* call `authoriseAccount()` / `authoriseManyAccounts()` / `blockAccount()`


##  Rate depends on sold amount

* 0-9000000 :  + 42%
* 9000001-18000000 : + 17%
* 18000000 - : + 0%
 
##  set the Rate 
* by CS user
* default is 3000
* call `setRate()` function , 0 < newRate <= 8000


## Finishing the sale (owner) - passes control of token back to the owner

* call `finishSale()` 

## Starting Trading

* call `startTrading()` on the TOKEN-contract




