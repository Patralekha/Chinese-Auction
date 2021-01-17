# Chinese-Auction
It is a conventional approach used for fundraising for a cause. The organizers collect items to be auctioned off for raising funds. Before the auction, the items for auctions are received and arranged each with a bowl to place the bid.  A chairperson is a special person among the organizers. She/he heads the effort and is the only person who can determine the winner by random drawing at the end of the auction. A set of bidders buy sheets of tickets with their money. The bidder’s sheet has a stub that identifies the bidder’s number, and tokens bought. 

This is a decentralized app based on blockchain,written in Javascript,Solidity and uses Smart Contracts and Truffle Suite.

Constructor  initializes the owner, register  allows (decentralized person) to register online to get the tokens and start bidding, bid function that lets a person bid, and finally revealWinner, to randomly choose the winner for the item auctioned. The Auction smart contract has Item and Person structs and other data items such as array of Items, array of Persons, array of winners, mappings, and beneficiary address. 
