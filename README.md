# BlockChain-based-Transaction

This project presents a simple blockchain wallet built using Python, Flask, and the pycryptodome library. It enables users to create new wallets, generate transactions between them, and view their transaction history in a secure environment.

## Installation

To get started with this project:

1. Clone the repository to your local machine:
git clone <repository-url>



2. Install the required libraries using pip:
pip install flask pycryptodome requests


## Usage

This application is divided into two parts: the blockchain client and the blockchain server. Both parts are essential for the full functionality of the blockchain wallet.

### Blockchain Client

The blockchain client allows users to interact with their wallet, create new wallets, and generate transactions.

1. Open a terminal and navigate to the project directory.
2. Run the blockchain client with the command:
python3 blockchain_client.py


3. Access the blockchain wallet by navigating to `http://localhost:8080` in your web browser.

#### Features

- **Create Wallets**: Users can generate new wallets with unique public and private keys.
- **Generate Transactions**: Allows transactions to be made between wallets.
- **View Transaction History**: Users can view a history of all transactions made.

### Blockchain Server

The blockchain server is responsible for processing and mining the transactions initiated by the client.

1. Open a new terminal window.
2. Navigate to the project directory.
3. Start the blockchain server using the command:
python3 blockchain.py


4. To access the blockchain server interface, visit `http://localhost:5000` in your web browser.

#### Features

- **Mining**: Processes and mines transactions initiated from the client side, adding them to the blockchain.

## Contributing

Contributions are welcome! Please feel free to fork this repository, make changes, and submit pull requests. If you have major changes to propose or find any bugs, please open an issue first to discuss.

## License

This project is open-sourced under the MIT License. See the LICENSE file for more details.
