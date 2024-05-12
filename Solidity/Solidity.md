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