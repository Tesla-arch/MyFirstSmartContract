A search for remix ide, and was directed to multiple search results where I selected the first link(https://remix.ethereum.org/)


Step 2
Selected workspaces from the opened window and created a new workspace named MyFirstSmartContract


Step 3
Proceeded to create a new file with the name SimpleStorage.sol with respect to the given assignment

step 4
Specifies the MIT Licensing and the Fragma version of the compiler, followed by creating my first smart contract named SimpleStorage which only declares a public unit variable named favouriteNumber.(NB: I also made refereces from the learning page for this part)

step 5
Proceeded to the compiler tab where I vividly make sure my stated compiler matches with the solidity compiler for the contract. (^0.8.25) in this case.

step 6
From the Deploy tab, I specifies the Remix VM(cacum) as my environment from which I proceed to deploy the contract


WEEK 2
Data types, Functions, Conditionals, Visibility, Arrays, Structs, and Enums


I utilize several variables to store and manage data. favoriteNumbers is a dynamic array that stores multiple favorite numbers of type uint256. The Person struct represents an individual with a name and favoriteNumber, and the people array holds instances of this struct. The ContractState enum defines two states: Active and Inactive, with the state variable tracking my current state.

I offer a range of functions for various operations. storeNumber sets a specific favorite number, while getFavoriteNumber retrieves it. isGreaterThan compares the favorite number with a given value, and sumToFavoriteNumber calculates the sum of numbers from 1 to the favorite number. 

Internal functions like internalFunction are accessible within  and my derived contracts, while external functions like externalFunction can be called from outside me. However The testExternalFunction demonstrates the usage of external function calls inside the same contract.

For data management, addFavoriteNumber adds a new favorite number to the favoriteNumbers array, and returnNumbers retrieves the entire array. addPerson adds a new person to the people array, while activateContract and deactivateContract control  isactive is use to define an enum to represent different states in the contract . 
