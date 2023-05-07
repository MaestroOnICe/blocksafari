# blocksafari

**blocksafari** is a web-based frontend to the blockchain in btcd.

**blocksafari** was a proof-of-concept for the early stages of [btcd](https://github.com/btcsuite/btcd).

![alt text](https://github.com/MaestroOnICe/blocksafari/blob/master/images/screenshot.png)

This code is not suitable for production use!

## Installation

Build from source

    1. Install Go according to the installation instructions here: http://golang.org/doc/install
    
    2. Clone the repository and build the application

## How to use

    Copy the sample-blocksafari.conf to blocksafari.conf

    Application Options:
    -C, --configfile    = Path to configuration file
        --listen        = Add an interface/port to listen on
    -c, --rpccert       = RPC server certificate chain for validation
    -s, --rpcserver     = IP and port for rpcserver
    -u, --rpcuser       = rpc username
    -P, --rpcpass       = rpc password

## License

blocksafari is licensed under the liberal ISC License.