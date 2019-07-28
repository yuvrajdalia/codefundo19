A blockchain based application which can help two functionalities:
1. track the expenses incurred by election booths to make election
process transparent economical.
2. help eligible voters to cast their vote in a secure way .

Expenses:
1.Every election booth will be assigned cash in the multiple of
cryptocurrency (ex: 50 lakhs will be 50k cryptos)

2.Every booth will have an unique id assigned according to the location

3.If they incur any expense they need to update it on a  node js
powered web application in the multiple of cryptos and upload the
bills with it.

4.Government crypto miners can verify the transaction and the bill and
can create a block with the hash of (booth id + primary key of
uploaded bills + amount) in a secured block chain.

5.At the end of elections the remaining cryptocurrency should be
returned to the government with official letter uploaded.

6.Government officials can be given access to track  the expenses
through a public ledger henceforth making the transactions transparent

Votes:
1.Every voter will cast a vote to a candidate and accordingly a
transaction with (booth id+ voter id + andiate) can be created and
added in blockchain.

2.Every voter id will be stored in a map which will be initialized
with false and changes to true if any voter casts his vote to prevent
duplicate voting which can again also be checked in the blockchain.

Solidity can be used to make smart contracts on the truffle framework
and metamask for voter ids.

