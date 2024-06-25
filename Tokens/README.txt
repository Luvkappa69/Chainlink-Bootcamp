https://docs.chain.link/
https://docs.chain.link/data-feeds
https://docs.chain.link/data-feeds/price-feeds/addresses?network=ethereum&page=1#sepolia-testnet

https://ethereum.org/en/developers/docs/standards/tokens/
https://eips.ethereum.org/EIPS/eip-20
https://wizard.openzeppelin.com/

remix = https://remix.ethereum.org/

MAKE FILE:
    Token.sol (GIT inside)

SOLIDITY COMPILER (remix):
    on green -> Compilation successful

DEPLOY & RUN TRANSACTIONS:
    GOTO -> Deployed Contracts(remix);


GET ADRESS -> COPY to EtherScan(sepolia!) to verify the code


MAKE FILE:
    TokenShop.sol (GIT inside)

On CONTRACT:
    SELECT TokenShop (NOT TokenInterface)

    Parameter: your_token_adress

On Token:
    TokenShop Needs AUTH for emiting Tokens!

    MINTER_ROLE
        0x9f2df0fed2c77648de5...
        grantRole
        role:
            0xd57f23a44a11039c3A9F...

account -> your_token_adress
should see -> Response: true

----

GOTO -> TokenShop

getChainlinkDataFeedLatestAnswer
252690577790
ETH/USD 2526.90577790

https://eth-converter.com/
Amount 0.01 ETH = 10000000000000000 wei

---

to know token receiving quantity:

tokenAmount
10000000000000000

Response
    1263
    = 12.63 tokens
