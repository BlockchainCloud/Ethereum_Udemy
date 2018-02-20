# Ethereum_Udemy
* [Udemy](https://www.udemy.com/ethereum-and-solidity-the-complete-developers-guide/learn/v4/t/lecture/8953560?start=0)
* [Ethereum Average BlockTime Chart](https://etherscan.io/chart/blocktime)
* [Remix](http://remix.ethereum.org/#optimize=false&version=soljson-v0.4.19+commit.c4cbbb05.js)
* https://www.icoalert.com/       
* http://rinkeby-faucet.com/send?address=0x5d9Ef44feEB2a5Fd7A29a49e9028BF5d67D96343
* https://buy.coinbase.com/widget?code=9ec56d01-7e81-5017-930c-513daa27bb6a&amount=0&address=0x5d9ef44feeb2a5fd7a29a49e9028bf5d67d96343&crypto_currency=ETH
* https://www.rinkeby.io/#stats
* https://gist.github.com/anonymous/22c13cfbb2a0d3b2942b59e931c6be1d
* [EtherScan](https://etherscan.io/)
* [Brian Holt](https://eventil.com/users/btholt)
* https://github.com/nebulasio
* http://web3py.readthedocs.io/en/stable/
* https://github.com/ethereum/web3.py
* [Ethereum on Wikipedia](https://en.wikipedia.org/wiki/Ethereum#Programming_languages)
* https://ethereum.org/token
* https://solidity.readthedocs.io/en/develop/
* https://developer.ibm.com/indexconf/workshops/
*     

##

```solidity
function getMessage() public view returns(string) {
  return message;
}
```

* public - anyone can call this function
* private - only this contract can call this function
* view - this function returns data and does not modify the contract's data
* constant - this function returns data and does not modify the contract data
* pure - function will not modify or even read the contract's data.
* payable - when someone call this function they might send ether along

(view and constant mean the same thing)
