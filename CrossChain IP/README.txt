https://github.com/solangegueiros/chainlink-bootcamp-2024

CHAINLINK DEV MERCH:
    https://dev.chain.link/
    https://chain.link/community/advocates
    https://chain.link/developers/experts


CONTENT SUMMARY:
    https://dev.chain.link/products/ccip
    https://docs.chain.link/ccip/tutorials/cross-chain-tokens
    https://docs.chain.link/resources/link-token-contracts#fuji-testnet
    https://docs.chain.link/ccip/supported-networks/v1_2_0/testnet#avalanche-fuji


ORIGIN BLOCKCHAIN -> Avalanche Fuji
DESTINATION BLOCKCHAIN -> Ethereum Sepolia

ADD AVAX TO METAMASK:
    https://chainlist.org/chain/43113
    [Add to Metamask]

GET TEST BALANCE IN ACCOUT:
    https://sepolia-faucet.pk910.de/
    https://sepoliafaucet.com/
    https://faucets.chain.link/
    https://sepolia.etherscan.io/address/0xA982C62E4c67aBEd0B4bC6f1d514DB5a48A8D372#writeContract

    LINK (gas token for CCIP) -> https://docs.chain.link/resources/link-token-contracts#fuji-testnet

    CCIP-BnM -> https://docs.chain.link/ccip/test-tokens#mint-tokens-in-the-documentation
    [Add CCIP-BnM to wallet]
    -Mint 1 CCIP-BnM Token-

remix = https://remix.ethereum.org/

SET ENVIRONMENT:
    Injected provider - Metamask
    Verify costum network (43113) network = Fuji

MAKE FILE:
    CCIPTokenSenderFujiSepolia.sol (GIT inside)

ref: 
https://docs.chain.link/resources/link-token-contracts#fuji-testnet
https://docs.chain.link/ccip/supported-networks/v1_2_0/testnet#avalanche-fuji

MAKE SURE TO BE ON Avax Fuji ((4313) network) in Metamask

SOLIDITY COMPILER (remix):
    on green -> Compilation successful


DEPLOY & RUN TRANSACTIONS:
    GOTO -> Deployed Contracts(remix)

Avax Fuji Block explorer -> https://testnet.snowtrace.io/

Fund contract -> CCIPTokenSenderFujiSepolia:
    Metamask = sendo to address (CCIPTokenSenderFujiSepolia address)
    [1: LINK,
     0.1: CCIP BnM token]

Deployed Contracts(remix):
    balancesOf: (CCIPTokenSenderFujiSepolia address)


SEND >> 0.01 (BnM da Fuji) >> TO >> Sepolia

https://eth-converter.com/
0.01 BnM = 10000000000000000 (wei)

transferToSepolia(
    _receiver -> metamask(YOUR_WALLET_ADDRESS)
    _amount -> 10000000000000000
)

ref : https://ccip.chain.link/

VERIFY TOKENS AFTER_CCIP:
    metamask -> Chain (Sepolia)
    metamask -> addToken(CCIP-BnM) -> https://docs.chain.link/ccip/test-tokens#mint-tokens-in-the-documentation
