# Auction-Smart-Contract

#Smart Contract for a Decentralized Auction

#The Auction has an owner (the person who sells a good or service), a start and an end date

#The highestBindingBid is the selling price and the highestBidder the person who won the auction

#People are sending ETH by calling a function called placeBid(). The sender’s address and the value sent to the auction will be stored in mapping variable called bids

#Users are incentivized to bid the maximum they’re willing to pay, but they are not bound to that full amount, but rather to the previous highest bid plus an increment. The contract will automatically bid up to a given amount

#After the auction ends the owner gets the highestBindingBid and everybody else withdraws their own amount
