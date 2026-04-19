# BoolArray.sol
BoolArray.sol
pragma solidity ^0.8.20;
contract BoolArray {
    bool[] public flags;

    function add(bool x) public {
        flags.push(x);
    }
}
