# votingblockchain
Dr. Jackson's Data Structures class implementation of a blockchain to store voting data

## Features
* GUI: 
  * Implemented using Java swing
  * Features:
    * Voter verification using blockchain
    * ID number (SSN)
    * Who they’re voting for
    * Timestamp
* Blockchain data structure
  * Implemented using Linked Lists
  * Stored: 
    * Custom voter class (stored as Merkle Tree)
    * A cryptographic hash of the previous block
    * Voter IDs (part of vote class)
* Hashing (verification)
  * SHA 256
* Web communication (multiple instances of the chain):
  * Unified time beat across all stations
  * Uploading of votes across all stations
