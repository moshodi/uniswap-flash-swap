# Uniswap Flash Swap Contract

This project calls the flash function on a Uniswap V3 pool and swaps the full amount withdrawn of token0 and token1 in the corresponding pools with the same token pair - but different fee tiers. After the swap, the contract will pay back the first pool and transfer profits to the original calling address.


