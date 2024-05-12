### Primitives and Data Structures
* `uint` = `uint256`
	* Other variants `uint8`, `uint16`, `uint32`
* `bool`
* `mapping (keyType => valueType)`
* `string`
### Visibility/Access Modifiers
*private*: like normal private modifier in other languages; restricted to within that contract
*internal*: like private but accessible by other contracts that inherit this one as well
*external*: can only be accessed from outside the contract
*public*: accessible anywhere

### State Modifiers
*view*: ensures that that no data will be changed in this function
*pure*: this function doesn't read/write data to/from the blockchain
Note:
* both *view* and *pure* do not cost gas if called **externally** from outside the function
* but they do cost gas if called **internally**
### Custom Modifiers
* Allows us to define logic which can be called before invoking the body of another function
* Good for:
	* ensure a condition is held before running a function
	* ex: checking permission
### Storage and Memory
* Memory = heap
* Storage = stored into the blockchain
	* Think database equivalent storage
### Events
* Can define events with parameters
* You can use the `emit` keyword and invoke an Event with those parameters
* On the frontend, you an define an event handler to process some logic for that event
### Gas

### Tokens
* *token*: a contract that that keeps track of who owns how much of that token
* Usually tokens have:
	* `transferFrom(address _from, address _to, uint256 _amount)` and `balanceOf(address _owner)`
* Different token standards for different use cases
	* Each standard has a set of methods we need to implement
	* Once you do it, your token will be supported by any exchange that supports that token logic
* To use a token contract, you need to copy the file over...

