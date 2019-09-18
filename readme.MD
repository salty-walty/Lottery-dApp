This is a very basic lottery smart contract deployed on the Ethereum rinkeby testnet

This contract sets up an Lottery which players spend ether to enter.

The manager of this contract can then call the pickWinner function to randomly select a 
winner of all the ETH that was placed into the smart contract.

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

 'Coming soon!'

Thanks for reading!