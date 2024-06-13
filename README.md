# Connection to MetaMask and Smart Contract Frontend

This is a simple frontend application that connects to MetaMask and interacts with a smart contract deployed on the Ethereum blockchain.
This project provides a simple HTML and JavaScript interface for interacting with a smart contract on the Ethereum blockchain using MetaMask and Web3.js.
The interface allows users to connect to MetaMask, connect to a specific smart contract, read data from the contract, and change data on the contract.

## File Structure

  -index.html: Main HTML file containing the structure and functionality of the web interface.

## Prerequisites
  -MetaMask extension installed in your browser.
  -An Ethereum account with sufficient funds for transactions.

## Running the Project

1- Clone the repository or download the HTML file

2- Open the HTML file:
      Simply open index.html in your web browser.
      
## Using the Interface

1- Connect to MetaMask:

  -Click the "DO METAMASK CONNECTION" button.
  -A MetaMask popup will appear asking you to connect your account.
  -After connecting, your Ethereum account address will be displayed.

2- Connect to the Smart Contract:

  -Click the "DO CONTRACT CONNECTION" button.
  -The interface will connect to the specified smart contract and display a confirmation message.
  
3- Read Data from the Smart Contract:

  -Click the "EXTRACT FROM CONTRACT" button to read a string value from the contract.
  -Click the "EXTRACT DATA FROM CONTRACT" button to read a number value from the contract.
  -The retrieved data will be displayed below the respective buttons.
  
4- Change Data on the Smart Contract:

  -Enter a new number in the input field.
  -Click the "CHANGE DATA ON THE SMART CONTRACT" button.
  -The entered number will be sent to the smart contract to update its state.

## Notes

1- Ensure MetaMask is properly installed and configured in your browser.

2- Make sure you have sufficient Ether in your account to cover gas fees for transactions.

3- Customize the contract address and ABI as per your specific smart contract deployment.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
  
  
  

## Author

Armaan Chahal
