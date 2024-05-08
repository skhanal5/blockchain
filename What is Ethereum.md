### What is Ethereum
* One POV: 
	* Deterministic but unbounded state machine
		* Globally accessible singleton state w/ a virtual machine that applies changes to it
* Another POV:
	* Open source, globally decentralized computing infrastructure
		* Executes smart contracts
		* Uses blockchain to sync and store system state changes
		* Uses ether to meter and constrain execution resource costs
### Compared to Bitcoin
* Not designed to be a digital currency payment network
* Ether is a utility currency to pay for use of Ethereum platform as the world computer
* Ethereum is a blockchain that runs a VM capable or running any type of code
	* It is Turing complete
### Components of a Blockchain
* P2P network of participants that moves transactions and blocks of verified transactions 
* Messages (transactions) representing state transitions
* Consensus rules
	* Determines what a transaction is and what makes a valid state transition
* State machine
	* processes transactions according to consensus rules
* Chain of cryptographically secured blocks
	* Journal/ledger of state transitions
* Consensus algorithm that decentralizes control
	* Forces nodes to cooperated in enforcing consensus rules
* Game-theory sound incentivization scheme
* OSS implementation of the above