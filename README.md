# Basic_Smart_Contract
I am currently honing my skills in Solidity, striving to master its fundamental concepts while adhering to the best practices. 

I am dedicated to continuously improving my skills, through regular practice with this type of code from FreeCodeCamp.org

In my example i define a smart contract called BasicSmartContract with a state variable counter that stores an unsigned integer. The contract also has a state variable owner that stores the address of the contract deployer.

The contract has a constructor that is automatically called when the contract is deployed. It initializes the counter to 0 and sets the owner to the address of the deployer, which is accessible via the msg.sender keyword.

The contract also has two functions. The incrementCounter function is a public function that can be called by anyone, but it includes a require statement to ensure that only the contract owner can actually increment the counter. The getCounter function is a public view function that allows anyone to retrieve the current value of the counter.






