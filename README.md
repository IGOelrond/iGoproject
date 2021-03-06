# Introduction

This repository holds a list of whitelisted tokens in the Elrond web tools. A whitelisted token can have website and socials URLs, a logo or a description, that will be displayed on Elrond products, such as the Elrond Explorer or the Web Wallet. The logos are also used in the Maiar App.

# Custom ESDT logo & description
Amplify your brand via the Elrond Network web tools & the Maiar App.

Add a logo, description & socials for your ESDT token.

Project owners can create a PR to this repo with the logo in .png and .svg format, as well as a .json file containing all the relevant information.

Here’s a prefilled template for the .json file to get you started:

```JSON
{
    "website": "https://www.elrondtoken.com",
    "description": "The ERD token is the utility token of Elrond Token",
    "social": {
        "email": "erd-token@elrond.com",
        "blog": "https://www.elrondtoken.com/ERD-token-blog",
        "twitter": "https://twitter.com/ERD-token-twitter",
        "whitepaper": "https://www.elrondtoken.com/ERD-token-whitepaper.pdf",
        "coinmarketcap": "https://coinmarketcap.com/currencies/ERD-token",
        "coingecko": "https://www.coingecko.com/en/coins/ERD-token"
    },
    "status": "active"
}
```

The ledgerSignature will be generated by Elrond. It will give your token “whitelist” status on the Ledger app and enable a more data rich flow for users storing your token on their Ledger hardware wallets. If one wants to set a Ledger signature, request it when opening a PR.

Submit your PR to this repo in order to request your tokens to be whitelisted.
