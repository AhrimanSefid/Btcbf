   [![CodeFactor](https://www.codefactor.io/repository/github/vlnahp/btcbf/badge/main)](https://www.codefactor.io/repository/github/vlnahp/btcbf/overview/main)
   
# Btcbf                                                                
A new way to support Btcbf and to be thankful to open source projects, is to buy the icon of Btcbf as NFT from [here](https://opensea.io/assets/matic/0x2953399124f0cbb46d2cbacd8a89cf0599974963/29326638034131043689181811786030646451603799113214635741285531928455660175365/). There are 5 ones available. Next versions will have new looking and higher value.
## **Description**

A fast and efficient bitcoin private key brute force written in python. The method is based on the generation of random private keys and their corresponding public address; then searching each through a list of addresses with a positive balance.

It is fast because the number of loops is multiplied by the number of addresses available in the list. It means if your CPU processes 500 loops per second; and 10000 addresses are in the list 5milion possibilities are checked per second(My tiny 2.9GHz dual-core CPU has the rate of 3200its/s, using a list of 10k addresses means 32milion possibilities are checked per second!). However, there are 2^256 possibilities to check; so not fast enough anyway.

## **Also can be used as wallet generator!**

Just type "gen" and a secure wallet is printed for you. The reason to use this method instead of the available websites and online wallets? Because you enter your email, use internet connections, etc. Your email can be hacked, your online wallet can be vulnerable to attacks, and many other ways that make them risky. Use my tool *-or any other tool that works the same way-* to generate a wallet offline in order to remain safe.   

## The Goal
The main goal is to prove bitcoin is secure. At least until the day that Quantum computers start working against it!:innocent:

## **Requirements**

  The "address.txt" file containing a list of public addresses is necessary in brute mode(Add as many as positive balance addresses possible to this file; this increases your chance of success, find more addresses [here](https://bitinfocharts.com/top-100-richest-bitcoin-addresses.html) ).

And run this command:

```$ pip install -r requirements.txt```  
```$ pip3 install -r requirements.txt``` 

```python Btcbf.py```
```python3 Btcbf.py brute1```


## **Usage**
Just execute this command:`$ python Btcbf.py`, Btcbf tells you what to do!
`"What do you want to do? <<options: [gen]: generate wallet address and private key, [brute1]: brute force bitcoin offline mode, [brute2]: brute force bitcoin online mode, [exit]: exit>>"` Type your desired action and follow instructions.(I love to interact with my program🙂)

### While brute1
Generated addresses are searched within the "address.txt". If any key is found; a text file named "foundkey.txt" containing the found private key and public address is saved.

### While brute2
Generated addresses are searched in the blockchain. **CAUTION** this will consume too much internet. Also it has limits and won't respond after certain number of requests sent.

### While gen
An address with its corresponding private key is printed.

### While exit
Exits!

## **Donation**

Make my BTC address a good option to be on the list!:cowboy_hat_face:


>BTC: 13r5Xr3D1j1RgwVt6KToXn8h9vqYb49eNx

>ETH: 0x25A296248f9F4a5e2343Dd19faF1b49594746620

>BCH: qq0ns64247xhqxjzv8cnjw7hl4scuc0jryzu37p4s9


## Latest Release
Link to latest release(v1.1.0): [link](https://github.com/vlnahp/Btcbf/releases/download/v1.2.1/Btcbf-windows64-v.1.2.0.tar.xz)

## :star:
Finally send me a _star:star2::arrow_upper_right:_ if you liked Btcbf!
