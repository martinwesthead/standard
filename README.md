# Ethereum Subscription Standard
the EIP which we will submit to the EIP repo.

See also: https://github.com/ethereum/EIPs/issues/948

# Working Group

* Scott Burke and Andrew Redden from BlockcrushR
* Kevin Owocki - Gitcoin
* Travis Mathis
* Rober Jorden
* Piotr Kosiński - ChronoLogic (Ethereum Alarm Clock)
* TODO- please add your name here

# Design Goals 

* Subscriptions
* Free Trials
* Based upon Ethereum
* TODO -- ad more

I think this is the wrong approach. Subscriptions can be extremely complicated add-ons, upgrade logic downgrade logic, cancellation logic, usage, overage, dunnings. However, I suggest that these should be left to implementations but supported by standards that allow:
* Wallets to be able to enummerate the list of subscription contracts they are associtated with
* User to be able to control the maximum amount that will be paid against any subscription in a given time (probably just a wallet feature)
* Wallet to be able top query the subscription for information (description, subscription owner etc).
* User to be able to cancel the subscription directly from the wallet

# Competing Implementations

See `standards/` dir.

* 8x
* BlockcrushR
* Piper Merriam implementation
