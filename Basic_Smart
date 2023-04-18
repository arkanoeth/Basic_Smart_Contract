pragma solidity ^0.8.0;

contract BasicSmartContract {
    // Define state variables
    uint public counter;
    address public owner;

    // Constructor - called when contract is deployed
    constructor() {
        counter = 0;
        owner = msg.sender;
    }

    // Function to increment the counter
    function incrementCounter() public {
        require(msg.sender == owner, "Only the contract owner can call this function.");
        counter++;
    }

    // Function to get the current counter value
    function getCounter() public view returns (uint) {
        return counter;
    }
}
