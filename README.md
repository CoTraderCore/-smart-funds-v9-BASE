# Run tests

```
NOTE: in separate console

0) npm i
1) npm run ganache  
2) truffle test
```

# Updates

```
1) Add role swaper which can trade, pool and call defi protocols.
2) Fix manager take cut for case manager take cut on the best profit period when profit go up then go down.
3) Optimize gas (remove or cache global vars in functions), for funds with 5-10 and more tokens gas now in n x less.
4) Fund creator can change fund name.
5) Add any fund asset type.
6) Remove Pools and Defi call
7) Remove tokens type stotage track (because we use for now only erc20)
8) Protect manager takeCut from flash loan atack
```



# Mainent deploy note

```
Don't forget add new addresses to new permittedAddresses contract
Don't forget set latest 1inch contract
```


# Addresses

```
root hash 

0x0818a8aae91a3d2da9c5c1afa60387c696272d27c11d376822e60219e9daebb7


Merkle Tree

https://basescan.org/address/0xc8a2ba3e9ce03f78551d7de5706cc275d4d3130f#code


UNI v2 router

https://basescan.org/address/0x4752ba5dbc23f44d87826276bf6fd6b1c372ad24#code


WETH

https://basescan.org/address/0x4200000000000000000000000000000000000006#code


UNI v2 factory 

https://basescan.org/address/0x8909Dc15e40173Ff4699343b6eB8132c65e18eC6#code


Price Portal 

https://basescan.org/address/0x3aE392A4c6a99FcB991E208f9D74618fff513834#code


Exchange Portal 

https://basescan.org/address/0x6F553184C04a4aD0b3551A4ff60FB73BB6E90408#code

```
