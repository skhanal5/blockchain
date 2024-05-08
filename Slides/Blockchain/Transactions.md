### Transactions
* Scan recipients address -> Submit transaction
* Receiver gets money
* Wallet has keys
	* Creates PKI signature address pairs
	* For each transaction, those keys creates a new PKI hashes signature for each transaction
* Transactions are submitted to mempool and miners submit new block of transactions
	* Transactions are confirmed through calculations
* Each block has a hash of the previous block (think linked list chain)
* Nodes maintain a "distributed ledger"