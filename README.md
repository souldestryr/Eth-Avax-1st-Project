# Smart Contract Management - ETH + AVAX

This is my 4th project for metacrafters.

## Description

The 4th project for Metacrafters consists of these 2 functionalities:
1. Smart contract has at least two functions
2. Value of the functions from the smart contract are visible on the frontend of the application

The skeleton code for this project can be found in through this github link: https://github.com/MetacrafterChris/SCM-Starter

## Getting Started

### Installing

* You can clone the repository using the ```git clone <link to repository>``` command through your terminal.
* You can also clone it through github desktop by clicking the down arrow button beside the code button and selecting open with github desktop

### Executing program

* Inside the project directory, in the terminal type: ```npm i```
* Open two additional terminals in your VS code
* In the second terminal type: ```npx hardhat node```
* In the third terminal, type: ```npx hardhat run --network localhost scripts/deploy.js```
* Back in the first terminal, type ```npm run dev``` to launch the front-end.
* Install the metamask extension in your web browser
* Add a network manually in your metamask with these fields
  - Name: (can be anything you would like)
  - RPC URL: http://127.0.0.1:8545/
  - Chain ID: 31337
  - Currency Symbol: ETH
* Click save
* Switch to your created network
* Go back to the terminal where you entered ```npx hardhat node``` and copy the private key of Account 0
* Import the account to Metamask

After executing these steps you will now be able to use the program by using the link given after your npm run dev command. It should look something like this
![image](https://github.com/LimyuA/Smart-Contract-Management---ETH-AVAX/assets/92149293/d1e2fa84-f8d8-42e3-8258-97843d5fb3de)
Open the http://localhost:3000 link using your web browser and from there you can now use the Metacrafters ATM!

## Help

Be sure to use Account 0 as it is the owner </br>
If you encounter an error where your nonce is too high, go to your Metamask, select settings->advanced and clear activity tab data. This error occurs when you use your account then close the application, then use the account again.

## Authors

Alan Gabriel Limyu (limyualan@gmail.com)


## License

This project is licensed under the Alan Gabriel Limyu License - see the LICENSE.md file for details
