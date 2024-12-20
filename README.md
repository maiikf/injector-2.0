# injector-2.0

This version (2.0) introduces several important updates and improvements over the previous release.

## What's New in Version 2.0

### 1. Improvements to the `convert_to_source` Function
The `convert_to_source` function, responsible for generating the AST (Abstract Syntax Tree), has been updated to support newer contracts. These changes ensure proper execution for modern contract implementations, enhancing the project's compatibility and reliability.

### 2. New Injection Files
New injection files have been added to the repository, extending the project's functionality. These files enable more flexible testing and simulation capabilities.

### 3. Modifications to Existing Files
Some existing injection files have been modified to meet new requirements and ensure greater consistency with the added features.

## Recommendations
To fully understand the changes made, it is recommended to review the previous version of the repository. This will provide a comprehensive context and insight into the impact of the updates introduced in version 2.0.

# Commands:

## to know what current version of Solidity compiler is:
solc --version

## install a new version:
solc-select install 0.8.21 

## to set what version of Solidity compiler should be used:
solc-select use 0.8.21

## to get a Compact AST structure of a smart contract
solc --ast-compact-json Abs5.sol > Abs5-ast.json

## inject a vulnerability into a smart contract:
python3 vul-1-3-1.py 3-1a_Fixed.sol
