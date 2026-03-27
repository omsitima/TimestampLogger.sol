# TimestampLogger.sol
How to deploy a contract on Base Chain TimestampLogger.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract TimestampLogger {
    uint[] public timestamps;

    function log() public {
        timestamps.push(block.timestamp);
    }
}
