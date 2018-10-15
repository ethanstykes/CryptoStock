# CryptoStock
A model of blockchain that can be used for stock trading and can replace stock exchanges

Based on: https://github.com/dvf/blockchain

Supports MacOS and Linux

Requirements:
Python 3.6+
Flask (pip install flask)
Node.js and npm

create a virtual environment ($python3 -m venv env)

$sudo npm install -g ttab (optional) for automatically configuring the network (change the virtual environment directory path)
$chmod +x config_network.sh
$./config_network.sh 

Or use $python blockchain.py -p <port (default:5000)> to configure required ports manually
(5000,5001 and 5002 -miners
5003 -trader)

run $npm install for adding the required node modules

PS: Payment verification function is incomplete (acknoledgement from the company is not included)

