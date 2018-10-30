# Paint Chauchas

The concept of painting or [coloring] (https://en.wikipedia.org/wiki/Colored_coin) refers to the process of identifying an item within a set. In this case "painting" a chaucha is giving a meaning beyond its financial value in the market.

Painting means that you can create your own exchange system. Maybe you have a store and want to reward your customers by offering discount coupons. Maybe you want to create a [local currency] (https://en.wikipedia.org/wiki/Local_currency). It can also be a prize that can be exchanged  by  the winner of a contest or the entry to a party or event.

Painting a chaucha opens the door to create new ways of exchanging value, regardless of the price of the chaucha.

Basically you are creating a *"token"* or chips that use the chaucha network  to verify their authenticity and prevent them from being used more than once.

## How does it work?
 
Nowadays there are different ways to paint cryptocurrencies, such as [Colored Coins](http://coloredcoins.org/documentation/).
 
However, the easiest way is the one described by the [Satokshi](http://satokshi.com) protocol.
 
This protocol simply says that: It is not necessary to paint each chaucha in order to identify it. You simply have to verify its root of origin to know if it is painted or not.

### Step 1 - Acquire Chauchas

The painted chauchas are traditional chauchas. The chaucha can be divided up to 8 times, then if we consider 0.000000001 CHA as the minimum unit we can create up to 100 000 000 painted chauchas using 1 CHA.

### Step 2 - Create the "Mother" Chauchera
 
This chauchera address will be considered as the original address of our painted chauchas or *"tokens"*. It is recommended to have access to the *private key*, so an *exchange* address is not recommended.
 
It is necessary that the mother chauchera has the amount of chauchas necessary to be able to create as many *tokens* as we need.
 
### Step 3 - Create "Children" Chaucheras
 
You must create a chauchera daughters. This will allow to distribute them easily. It is recommended to have access to the *private key* if you want, for example, to deliver the tokens in the form of [paper wallets](/sec).
 
It is very important that these addresses are used separately from other chaucheras. It is also important that they have no other transactions than those belonging to the painting process. This is to facilitate the search and the organization.
 
### Step 4 - Send the Painted Chauchas
 
This will be the genesis transaction of our painted chauchas. From this transaction, a record of the location of the painted chauchas can be kept.

0.00000001 CHA will be sent to each daughter address that should contain a painted chaucha.

### Step 5 - Delivery of the Painted Chauchas

The *private key* associated with a child chauchera can be delivered or the painted chaucha can be sent to other addresses. The important thing is that there is now a record of the initial transaction. As long as the chaucha has in its historical record the origin of the genesis transaction, it can be considered as valid.

### Step 6 - Collection of the Painted Chauchas

To consider a shag painted as "used" in a simple way, we can design target chaucheras. When people send painted chauchas, it is said that they can collect their prize, discount, product or service.

## Considerations

While we can make a verbal agreement to validate the value associated to a painted chaucha, as this value being subject to the non-digital world it is advised to back it up with some notarized act or one of similar nature.

We can also carry out an operation with [OP_RETURN](https://iot.chaucha.cl) that registers a permanent message in the chaucha blockchain using the mother chauchera. This message can specify the commitment and the rules to consider the painted chauchas as valid.

It is advisable to use one or many mother chaucheras and create a [multiple private key](https://en.bitcoin.it/wiki/multisignature) transaction in order to prevent the risk of theft and creation of unofficial painted chauchas.

Lastly, specific rules can be created for these painted chauchas. For example, them not being able for use before a specific date or expire after a specific time. For this it is necessary to program the transaction rules using [Script](https://en.bitcoin.it/wiki/script).

## Analyzing the Network
A great way to analyze the network in real time is to use the api of [insight] (http://insight.chaucha.cl/). You can see the [documentation here] (https://github.com/bitpay/insight). The version adapted to chaucha is
available at [https://github.com/proyecto-chaucha/chaucha-insight](https://github.com/proyecto-chaucha/chaucha-insight).

Using these tools one can listen to websocket events, detecting a transaction to the painted address and analyzing the path traveled by the painted chauchas.

## Links

- [https://en.wikipedia.org/wiki/Colored_coin](https://en.wikipedia.org/wiki/Colored_coin)
- [https://github.com/jl2012/bips/blob/color/bip-color.mediawiki](https://github.com/jl2012/bips/blob/color/bip-color.mediawiki)
- [http://coloredcoins.org/documentation/](http://coloredcoins.org/documentation/)
- [http://satokshi.com](http://satokshi.com)

