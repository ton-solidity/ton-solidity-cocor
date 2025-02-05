# ton-solidity-cocor
This repo is an attempt to create an adequate CoCo/R LL(1) grammar for Solidity.

It will not allow to easily port original Ethereum Solidity codebases, pity. But it's a quick and easy way to port Solidity to TVM, using the CoCo/R + LLVM way. Can be continually improved to port more of existing Sol code.

In parallel, I will use the [existing 500MB Ethereum Solidity codebase](https://github.com/ton-solidity/ethereum-solidity/releases/tag/v0.8.28) at my project [ton-solidity-eth](https://github.com/ton-solidity/ton-solidity-eth) to try writing a translator that matches original Solidity semantics better.

 * <i>Project Status:</i> Work In Progress.
