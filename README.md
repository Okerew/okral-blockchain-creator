# okral-blockchain-creator
A block chain creator I created, I am new in this so this might be not the best
________________________
How to create a blockchain
---------------
To create a blockchain firstly install requirements which are not already installed then run the main.py 
<br>
Export blockchain to a blockchain.json file `curl http://127.0.0.1:3000/export -o blockchain.json`
<br>
Import blockchain `curl -X POST -H "Content-Type: application/json" -d @blockchain.json http://127.0.0.1:3000/import`
