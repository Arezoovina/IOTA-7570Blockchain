
# IOTA Address Graph
## Table of contents
* [Intoroduction](#Introduction)
* [Technologies](#technologies)
* [Lunch](#Lunch)
* [Code](#Code)
## Introduction
In this project, we aim to create a IOTA address graph. To this aim, we used Hornet 0.5.6 to connect to the IOTA tangle to create the IOTA address graph. Hornet is an API for working with iota data, and it comes with a lot of advantages as it is lightweight, and it enables the users to run their own node. 
## Technologies
- Hornet 0.5.6
- Python 3.7.0 

## Data
We set up Hornet 0.5.6 to start working with IOTA data. There are 1000 transactions (.txt file of list of transaction is availible).
In first part of the code we printed all transactions as nodes of the graph. Transactions are identified by their hash address, like 'BR9FRRIEHRJGDZKAPHLBFBBJWUIYNXDXOXMWORVYRTZYXSQESRM9RUWLNEXQNWTUIABFGBNFMFVY99999'.
## Setup
First we have to execute hornet. If you are using windows you just have to execute hornet.exe.  For other operating sysyems there are additional steps required which the instruction are available at :https://docs.iota.org/docs/hornet/1.1/tutorials/install-hornet . Once the hornet is executed go to this address :localhost:8081/dashboard on your browser and wait until it states that it is synced (on a green icon) on your browser. After that you can start executing the python codes.

## Code
The project includes three parts: 
- Receiving the milestones transactions
- Extracing tipstransactions
- Graph
