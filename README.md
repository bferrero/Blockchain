# Blockchain

## How to mine Ethereum in your computer

#### Prepare environment for RegTest (Windows)

1. Install Cmder (http://cmder.net/)
2. Install Go (https://golang.org/doc/install)
3. Install Nvm (https://github.com/coreybutler/nvm-windows/releases)
  * Run commands:
    * nvm install node
    * nvm list
    * nvm use v9.6.1
4. Install Ethereum (with puppeth) (https://geth.ethereum.org/downloads/)
  * To install puppeth, you must activate "Development tools" during installation.
  * Test: run the following command: geth version.
5. Generate hash (SHA256) with the word used for consensus from any website. (I used https://passwordsgenerator.net/sha256-hash-generator/)
6. Generate "Genesis.json" file with puppeth.
 * Open a terminal and run the following commands:

