# learning

Digital currency and online payment system that uses encryption techniques toRegulate the generation of units of currencyVerify the transfer of fundsDecentralized virtual currency.Mining: anyone can use their machines to verify and record payments into the public ledger.
Crypto-currencyBitcoin(BTC), Litecoin, etc...Bitcoin protocol and clientSoftwareprograms that conduct transactionsBitcoin blockchainUnderlying decentralized ledge Ownership of bitcoin is established through private and public keys, wallet with a bitcoin address. Private Key => Public Key => Bitcoin Address (Wallet) using One-way Encryption. 
Miners validate new transactions and record them on the global ledger.It is an operation of inverse hashing to determines a nonce.Miners receive two types of rewards: new coins created with each new block and transaction fees.First, miners complete to solve a difficult mathematical problem based on cryptographic hash algorithm (known as Proof-of-Work).The competition to solve the PoWalgorithm is to earn the reward and the right to record transactions on the blockchain.Transactions that added to the blockchainare considered “confirmed”.

Proof-of-Work vs Proof-of-Stake AlgorithmMathematical puzzle which is hard to solve on the Miner side but easy to check for the network.Miners compete to be the first to find a solution for the puzzle. 
BlockchainSmart ContractsIF ( user.sendsMoney(anotherUserId) ){runContract();}funcrunContract() {accountsCheck();bbalanceCheck();Transfer();}A piece of code that lives on a blockchain, not a server.When a pre-programmed condition is triggered, the smart contract executes the corresponding contractual clause.No third party trust is required.No central point of failure.


tampered_Tree = Jae_MerkTree()
	tampered_Tree_transaction = ['a','b','c','d','f']
	tampered_Tree.listoftransaction = tampered_Tree_transaction
	tampered_Tree.create_tree()
	tampered_Tree_past_transaction = tampered_Tree.Get_past_transacion()
	tampered_Tree_root = tampered_Tree.Get_Root_leaf()



To keep data geographically close to users.•To allow the system to continue working even if some parts of the system have failed.•To scale out the number of nodes that can serve read queries. Two servers play “master” and “slave” roles.•Clients send operations (both READ and WRITE) to Leader.•Leader forwards WIRTE operations to one or more followers.•Finally, leader replies to client. 
Non-deterministic operations.•No network partition—if leader cannot reach to followers, then the data will be inconsistent.•State transfer between leader and followers.•How to bring up a new follower after existing follower becomes leader.
Hashing is a process that maps data of a variable length to data of a fixed length.•The values returned by a hash function are called hashes, hash values, hash codes, hash sums, or checksums.
If the keys are fixed-length strings (E.g. phone numbers or user ids), then a hash function needs to map roughly the same number of keys to each hash value.•A common way of load balancing across n cache nodes is to put object o in cache node number hash(o) mod n.

When you add or remove from cache nodes, every object needs to hash to a new location.•This can be catastrophic since the originating content servers are swamped with requests from the cache machines.
