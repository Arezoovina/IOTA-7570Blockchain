
# IOTA Address Graph
## Table of contents
* [Intoroduction](#Introduction)
* [Technologies](#technologies)
* [Lunch](#Lunch)
* [Code](#Code)
## Introduction
In this project, we aim to create an IOTA address graph. To this aim, we used Hornet 0.5.6 to connect to the IOTA tangle to create the IOTA address graph. Hornet is an API for working with iota data, and it comes with many advantages as it is lightweight and enables the users to run their node. 
## Technologies
- Hornet 0.5.6
- Python 3.7.0 

## Data
We set up Hornet 0.5.6 to start working with IOTA data. There are 1000 transactions (the .txt file of the list of transactions is available).
In the first part of the code, we printed all transactions as nodes of the graph. Transactions are identified by their hash address, like 'BR9FRRIEHRJGDZKAPHLBFBBJWUIYNXDXOXMWORVYRTZYXSQESRM9RUWLNEXQNWTUIABFGBNFMFVY99999'.
## Setup
First, we have to execute the Hornet. If one is using Windows, it is enough to execute hornet.exe.  For other operating systems, there are additional steps required, which the instruction is available at https://docs.iota.org/docs/hornet/1.1/tutorials/install-hornet. Once the Hornet is executed, go to this address:localhost:8081/dashboard on the browser and wait until it states that it is synced (on a green icon) on your browser. After that, you can start executing the python codes.

## Code
The project includes three parts: 
- Receiving the milestones transactions
- Extracting tips transactions
- Graph
