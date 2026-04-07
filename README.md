# HelloMessage.sol
HelloMessage.sol7
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract HelloMessage {
    string public message;
    function setHello() public { message = "Hello"; }
}
Add number operations contracts
Simplify function logic
Fix contract deployment issue
