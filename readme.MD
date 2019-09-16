This is a very basic smart contract deployed on the Ethereum rinkeby testnet

This contract sets up an "Inbox" with a message variable that can be viewed and modified

If you wanted to deploy this contract, you would want to first install the dependencies 
with:

```npm install```

Next you would need to install metamask and load it up with rinkeby test ether, 
these can be obtained at: https://faucet.rinkeby.io/

After installing and loading up metamask, sign up for infura at: https://infura.io
Once signed up for infura, create a new project and get a rinkeby endpoint URL

With your metamask seedphase and infura rinkeby endpoint URL end hand, you can go 
into deploy.js and replace the strings on lines 6 & 7 with your metamask seedphrase
and your rinkeby endpoint URL, remeber to keep these secret.

After deploy.js is updated with your credentials, you can run:

``` node deploy.js```

If successfull, after a short wait this will return "Contract deployed to 0x......"

You can see my deployment of this contract at: 

https://rinkeby.etherscan.io/address/0x14422b5cea6ae9fd008976c90dc5b5645efa26d9

Thanks for reading!