# Smart Contract Analysis

## Introduction

**Protocol Name:** Uniswap V3  
**Category:** DeFi  
**Smart Contract:** NonFungiblePositionManager  

## Function Analysis

**Function Name:** mint  
**Block Explorer Link:** [Uniswap V3 NonFungiblePositionManager](https://etherscan.io/address/0xC36442b4a4522E871399CD717aBDD847Ab11FE88#code)  
**Function Code:**
```solidity
function mint(MintParams calldata params)
    external
    payable
    returns (uint256 tokenId, uint128 liquidity, uint256 amount0, uint256 amount1);
