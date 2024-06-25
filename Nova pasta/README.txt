https://github.com/solangegueiros/chainlink-bootcamp-2024

CONTENT SUMMARY:
    IPFS ->> INTERPLANETARY FILE SYSTEM
        ex: 
            piñata
            infura
            quicknode
            nft.storage
            web3.storage
            thirdweb storage

    https://docs.opensea.io/docs/metadata-standards

CHAINLINK DEV MERCH:
    https://dev.chain.link/
    https://chain.link/community/advocates
    https://chain.link/developers/experts


GET TEST BALANCE IN ACCOUT:
    https://sepolia-faucet.pk910.de/
    https://sepoliafaucet.com/
    https://faucets.chain.link/
    https://sepolia.etherscan.io/address/0xA982C62E4c67aBEd0B4bC6f1d514DB5a48A8D372#writeContract


Metamask -> chain(Sepolia) 

remix = https://remix.ethereum.org/


SET ENVIRONMENT:
    Injected provider - Metamask
    should get "Sepolia"

MAKE FILE:
    PhotoAlbum.sol (GIT inside)

SOLIDITY COMPILER (remix):
    on green -> Compilation successful

DEPLOY & RUN TRANSACTIONS:
    GOTO -> Deployed Contracts(remix)
    SET Parameter -> updateInterval = 120
    (120s = 2 minutes)


EXPAND PhotoAlbum:
    BalanceOf -> Metamask(address)

    Mint +2 NFTs on Album:
        SafeMint -> Metamask(address)

        SEARCH (PhotoAlbum address):
            MARKET -> https://testnets.opensea.io/
            BLOCK_EXPLORER-> https://sepolia.etherscan.io/
        
        ex: https://testnets.opensea.io/collection/photo-album-chainlink-bootcamp-2024-108

BACK TO REMIX:
    photoAlbumIndex(
        Index: 1,
        Returna: 0,
        "1st JSON"
    )

    rotatePhoto(Index: 1)

    open Index 1 -> example: https://testnets.opensea.io/assets/sepolia/0x40a5d4055c2b460800a49f4da5ae2c38548033d5/1

    >> Refresh metadata
    >> Refresh page

        


