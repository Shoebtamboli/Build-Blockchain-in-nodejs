## Build blockchain in nodejs
    Simple blockchain example with 5 nodes.

### How to run
    git clone
    npm install 
    npm run node_1
    npm run node_2
    npm run node_3
    npm run node_4
    npm run node_5

    make sure all network nodes are running.

### APIs

|  Method   |                               |
| ----------| ----------------------------- |
| GET       | /blockchain                   |
| POST      | /transaction                  |
| POST      | /transaction/broadcast        |
| GET       | /mine                         |
| POST      | /receive-new-block            |
| POST      | /register-and-broadcast-node  |
| POST      | /register-node                |
| POST      | /register-nodes-bulk          |
| GET       | /consensus                    |
| GET       | /block/:blockHash             |
| GET       | /transaction/:transactionId   |
| GET       | /address/:address             |
| GET       | /block-explorer               |  


### To run block-explorer
http://localhost:{PORT}/block-explorer

### 

![Alt text](screenshot/explorer_1.png?raw=true "Address")

![Alt text](screenshot/explorer_2.png?raw=true "Transaction")

![Alt text](screenshot/explorer_3.png?raw=true "Block")
