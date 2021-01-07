# decentralized_marketPlace

Readme file with steps to understand working and running of the project:<br />
Some prerequisite to be installed on systems are:<br />
Node.js (https://nodejs.org/en/) latest version of the Node.js from the website.<br />
NPM (https://www.npmjs.com/get-npm).<br />
Ganache-CLI (https://github.com/trufflesuite/ganache-cli/blob/develop/README.md). <br />
Metamask (https://metamask.io) web extension of the metamask.<br />
The working and running of the project:<br />
1. Unzip the D-commerce and you will have all the files in different folders.<br />
2. Make sure to open the project in any IDE like VS studio code and be in the folder of
Dcommerce. If not use -> cd Dcommerce , after opening project.<br />
3. Now to install all the latest node module use the command -> npm install.<br />
4. For installing truffle use -> npm install -g truffle.
With truffle we can perform various functions such as smart contract management, Automated testing, deployment and Migration, development truffle console.
5. Once we download the Ganache from the website, run the installer and then set up a workspace we named (in our case as “D-commerce”) which is our personal block chain.
6. Install the metamask as an extension. Metamask will also allow to manage the Ethereum account when connected to the blockchain, as well as manage the funds that will be needed to pay for transactions.
7. All the dependencies for different uses are already in the package.json file. Npm install will install them in the system.
8. In truffle-config.js the primary responsibility of this file is to connect the project to the blockchain network, we already set this up to connect to our Ganache personal blockchain, i.e., “http:127.0.0.1:7545”.
9. The smart contracts are in the src directory so that they can be accessed by our react application.
   Truffle (https://truffleframework.com/docs/truffle/getting-started/installation), latest
  version of Truffle.
    
10. To compile and check if smart contract works use-> truffle compile
11. Now migrate run the migrations like this -> truffle migrate
12. To check the smart contract we can check on console using-> truffle console
13. In Marketplace.test.js we wrote all our tests in Javascript inside this file with the Mocha testing framework and the Chai assertion library to test the smart contract use-> truffle test
14. If any change in smart contract we can rerun migrations using->
truffle migrate -- reset.
15. Make sure to add any 2 accounts from Ganache local workspace to metamask and with Network ID and ChainID or by using mnemonics connect the local network http:127.0.0.1:7545, as also shown in demo.
16. After connecting the metamask with Ganache run the project client side with command: npm run start.
