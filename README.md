# START-Summit-2017-Blockchain-Machine-Learning-Workshop
Presentation Material and Sample Code from the Blockchain and Machine Learning Workshop at START Summit 2017 in Switzerland

# Intro
The purpose of this code is to demonstrate in a simple example, how to bring Blockchain technology, smart contracts and Machine Learning together.
It implements a simple chat client that can transmit messages, images and tags to the Blockchain. Tags are automatically extracted via a simple Deep Neural Network using the Keras Python Package with Tensorflow backend.
In addition to just sending messages, the client also supports listening for new messages on the Blockchain from other participants.
For details, please view the workshop presentation.

# Files
- runTestnet.sh: launches a local development Blockchain for easy testing
- contract.sol: contains the smart contract code in solidity language
- installContract.py: Python script for sending our contract to the Blockchain
- user.py: Python script that contains the actual chat client
- classify.py: Python script to classifiy an image file

# Setup
I really recommend using Linux at this point. The installation guidelines will focus on Ubuntu Linux 16.04 LTS, but should be similar for other distributions.


