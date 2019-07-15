
# Zilla-Chain
## Specifications and uses of the ZILLA Utility Chain

Zilla Chain version 0.1.0 beta

"ZILLA" is the ticker for the ChainZilla token. ZILLA is a utility token, which gives our users access to the services provided by ChainZilla.io


## What is a utility token?

A utility token represents access to a future product or service. When you buy a utility token, you are buying your “right” to use a service that’s being developed by a project once it’s finished and launched. ChainZilla plans to extend the functionalities and implement them into the company structure and services we offer. 

## How may I use the ZILLA utility token?

ZILLA token holders are able to exchange their tokens for ChainZilla services such as Komodo notarizations, blockchain deployment, app & web development, and cyber security services. In addition we plan to establish strong governance over our operations, token holders will be able to participate in community votes when ChainZilla deems appropriate.

## ZILLA Mainnet Tech Specification
=======
[![Build Status](https://travis-ci.org/KomodoPlatform/komodo.svg?branch=dev)](https://travis-ci.org/KomodoPlatform/komodo)
---
![Komodo Logo](https://i.imgur.com/vIwVtqv.png "Komodo Logo")


## Komodo

This is the official Komodo sourcecode repository based on https://github.com/jl777/komodo. 

## Development Resources

- Komodo Website: [https://komodoplatform.com](https://komodoplatform.com/)
- Komodo Blockexplorer: [https://kmdexplorer.io](https://kmdexplorer.io/)
- Komodo Discord: [https://komodoplatform.com/discord](https://komodoplatform.com/discord)
- Forum: [https://forum.komodoplatform.com](https://forum.komodoplatform.com/)
- Mail: [info@komodoplatform.com](mailto:info@komodoplatform.com)
- Support: [https://support.komodoplatform.com/support/home](https://support.komodoplatform.com/support/home)
- Knowledgebase & How-to: [https://support.komodoplatform.com/en/support/solutions](https://support.komodoplatform.com/en/support/solutions)
- API references & Dev Documentation: [https://docs.komodoplatform.com](https://docs.komodoplatform.com/)
- Blog: [https://blog.komodoplatform.com](https://blog.komodoplatform.com/)
- Whitepaper: [Komodo Whitepaper](https://komodoplatform.com/whitepaper)
- Komodo Platform public material: [Komodo Platform public material](https://docs.google.com/document/d/1AbhWrtagu4vYdkl-vsWz-HSNyNvK-W-ZasHCqe7CZy0)

## List of Komodo Platform Technologies

- Delayed Proof of Work (dPoW) - Additional security layer and Komodos own consensus algorithm  
- zk-SNARKs - Komodo Platform's privacy technology for shielded transactions  
- Tokens/Assets Technology - create "colored coins" on the Komodo Platform and use them as a layer for securites  
- Reward API - Komodo CC technology for securities  
- CC - Crypto Conditions to realize "smart contract" logic on top of the Komodo Platform  
- Jumblr - Decentralized tumbler for KMD and other cryptocurrencies  
- Assetchains - Create your own Blockchain that inherits all Komodo Platform functionalities and blockchain interoperability  
- Pegged Assets - Chains that maintain a peg to fiat currencies  
- Peerchains - Scalability solution where sibling chains form a network of blockchains  
- More in depth covered [here](https://docs.google.com/document/d/1AbhWrtagu4vYdkl-vsWz-HSNyNvK-W-ZasHCqe7CZy0)  
- Also note you receive 5% Active User Reward on your balance.  
[See this article for more details](https://support.komodoplatform.com/en/support/solutions/articles/29000024515-how-to-claim-the-kmd-active-user-reward-in-agama)

## Tech Specification
- Max Supply: 200 million KMD
- Block Time: 60 seconds
- Block Reward: 3 KMD
- Mining Algorithm: Equihash

## About this Project
Komodo is based on Zcash and has been extended by our innovative consensus algorithm called dPoW which utilizes Bitcoin's hashrate to store Komodo blockchain information into the Bitcoin blockchain. Other new and native Komodo features are the privacy technology called JUMBLR, our assetchain capabilities (one click plug and play blockchain solutions) and a set of financial decentralization and interoperability technologies. More details are available under https://komodoplatform.com/ and https://blog.komodoplatform.com.
>>>>>>> upstream/master

    Max Supply: 11 Million ZILLA
    Block Time: 1M
    Block Reward: 0.00001
    Mining Algorithm: Equihash
    RPCPORT: 10041
    This version of Komodo Independent Chain contains Bitcore support for komodo and all its assetchains.
    
## TESTZILLA Tech Specification

    Max Supply: 11 Million ZILLA
    Block Time: 1M
    Block Reward: 0.00001
    Mining Algorithm: Equihash
    RPCPORT: 8250
    This version of Komodo Independent Chain contains Bitcore support for komodo and all its assetchains.    

## CHAINZILLA Resources

    Website: https://www.chainzilla.io
    Twitter: https://twitter.com/Chainzillaio
    HelpDesk: http://support.chainzilla.io/support/home
    BitcoinTalk: https://bitcointalk.org/index.php?topic=4456446.msg39886899#msg39886899
    Email: contact@chainzilla.io  
    
## About CHAINZILLA

ChainZilla was conceived with the purpose of raising the bar in terms of the quality of the applications and blockchains being used in the industry. Additionally, our goal is to facilitate the use of open source technology such as atomic swaps, native blockchain deployment, and smart contracts in different sectors. These fields includes real estate, finance, non-profit, and academic. Corporations are dedicating resources to find out how much business they can gain by adopting blockchain technology. Blockchain has the potential of a trans-formative technology. It allows solving two important issues, those of centralized trust and the speed of operations. Blockchain will not remain a purely fintech phenomenon and has set itself up for wider B2B applications in the coming decade. ChainZilla will play a major role in bringing blockchain technology to regions that are still in their infancy in regards to blockchain and fintech technology such as LATAM. 
## Getting started

Dependencies
------------
Install Komodo: https://docs.komodoplatform.com/en/latest/komodo/install-Komodo-manually.html#installing-komodo-manually

After installing the Komodo repository, follow the steps:

`cd Komodo/src`

# Now run the following command to start the ZILLA chain or TESTZILLA chain. 

# Mainnet
`./komodod -ac_name=ZILLA -ac_supply=11000000 -addnode=54.39.23.248 -gen &`

# Testnet
`./komodod -ac_name=TESTZILLA -ac_supply=11000000 -addnode=158.69.0.53 &`

Once the ZILLA chain is synched, you are able to use the wallet functionality

# Commands 
In order to perform a command you must navigate to

`cd komodo src`

and execute commands with the following prefix

`./fiat-cli ZILLA`

i.e. Command to get wallet info

`./fiat-cli ZILLA getinfo`

# Main Commands
## Wallet
- getinfo 
- backupwallet "destination"
- dumpprivkey "zillaaddress"
- dumpwallet "filename"
- encryptwallet "passphrase"
- getaccount "ZILLA_address"
- getaccountaddress "account"
- getaddressesbyaccount "account"
- getbalance ( "account" minconf includeWatchonly )
- getnewaddress ( "account" )
- getrawchangeaddress
- getwalletinfo
- importaddress "address" ( "label" rescan )
- importprivkey "komodoprivkey" ( "label" rescan )
- importwallet "filename"
- listaccounts ( minconf includeWatchonly)
- listaddressgroupings
- listlockunspent
- listtransactions ( "account" count from includeWatchonly)
- listunspent ( minconf maxconf  ["address",...] )
- lockunspent unlock [{"txid":"txid","vout":n},...]
- resendwallettransactions
- sendfrom "fromaccount" "toZILLAaddress" amount ( minconf "comment" "comment-to" )
- sendmany "fromaccount" {"address":amount,...} ( minconf "comment" ["address",...] )
- sendtoaddress "ZILLA_address" amount ( "comment" "comment-to" subtractfeefromamount )
- setaccount "ZILLA_address" "account"
- settxfee amount
- signmessage "ZILLA address" "message"

## Zero Knowledge Addresses
- z_exportkey "zaddr"
- z_exportviewingkey "zaddr"
- z_exportwallet "filename"
- z_getbalance "address" ( minconf )
- z_getnewaddress
- z_getoperationresult (["operationid", ... ])
- z_getoperationstatus (["operationid", ... ])
- z_gettotalbalance ( minconf includeWatchonly )
- z_importkey "zkey" ( rescan startHeight )
- z_importviewingkey "vkey" ( rescan startHeight )
- z_importwallet "filename"
- z_listaddresses ( includeWatchonly )
- z_listoperationids
- z_listreceivedbyaddress "address" ( minconf )
- z_mergetoaddress ["fromaddress", ... ] "toaddress" ( fee ) ( transparent_limit ) ( shielded_limit ) ( memo )
- z_sendmany "fromaddress" [{"address":... ,"amount":...},...] ( minconf ) ( fee )
- z_shieldcoinbase "fromaddress" "tozaddress" ( fee ) ( limit )
- zcbenchmark benchmarktype samplecount
- zcrawjoinsplit rawtx inputs outputs vpub_old vpub_new
- zcrawkeygen
- zcrawreceive zcsecretkey encryptednote
- zcsamplejoinsplit

## Blockchain
- getbestblockhash
- getblock "hash|height" ( verbose )
- getblockchaininfo
- getblockcount
- getblockhash index
- getblockhashes timestamp
- getblockheader "hash" ( verbose )
- getdifficulty
- getspentinfo

## Control 
- getinfo
- help ( "command" )
- stop

## Generating
- generate numblocks
- getgenerate
- setgenerate generate ( genproclimit )

## Network
- addnode "node" "add|remove|onetry"
- clearbanned
- getconnectioncount
- getdeprecationinfo
- getnettotals
- getnetworkinfo
- getpeerinfo
- listbanned
- ping
- setban "ip(/netmask)" "add|remove" (bantime) (absolute)

## For all commands type the following
=======

### Dependencies

```shell
#The following packages are needed:
sudo apt-get install build-essential pkg-config libc6-dev m4 g++-multilib autoconf libtool ncurses-dev unzip git python python-zmq zlib1g-dev wget libcurl4-gnutls-dev bsdmainutils automake curl
>>>>>>> upstream/master
```
cd komodo/src
./komodo-cli -ac_name=ZILLA help
```
## About Komodo

<<<<<<< HEAD
Komodo is based on Zcash and has been  by their innovative consensus algorithm called dPoW which utilizes Bitcoin's hashrate to store Komodo blockchain information into the Bitcoin blockchain. Other new and native Komodo features are the privacy technology called JUMBLR or our assetchain capabilities (one click plug and play blockchain solutions). More details are available under https://komodoplatform.com/.

## List of Komodo Platform Technologies

    Delayed Proof of Work (dPoW) - Additional security layer.
    zk-SNARKs - Komodo Platform's privacy technology
    Jumblr - Decentralized tumbler for KMD and other cryptocurrencies
    Assetchains - Easy way to fork Komodo coin
    Pegged Assets - Chains that maintain a peg to fiat currencies
    Peerchains - Scalability solution where sibling chains form a network of blockchains
    More in depth covered here
    Also note you receive 5% APR on your holdings. See this article for more details


## Komodo Development Resources

    Komodo Web: https://komodoplatform.com/
    Organization web: https://komodoplatform.com/
    Forum: https://forum.komodoplatform.com/
    Mail: info@komodoplatform.com
    Support: https://support.komodoplatform.com/support/home
    Knowledgebase & How-to: https://komodoplatform.atlassian.net/wiki/spaces/KPSD/pages
    API references: http://docs.supernet.org/ #Not up to date.
    Whitepaper: Komodo Whitepaper
    Komodo Platform public material: Komodo Platform public material


Deprecation Policy
------------------

This release is considered deprecated one year after the release day. There
is an automatic deprecation shutdown feature which will halt the node some
time after this one year period. The automatic feature is based on block
height and can be explicitly disabled.
=======
### Build Komodo

This software is based on zcash and considered experimental and is continously undergoing heavy development.

The dev branch is considered the bleeding edge codebase while the master-branch is considered tested (unit tests, runtime tests, functionality). At no point of time do the Komodo Platform developers take any responsbility for any damage out of the usage of this software. 
Komodo builds for all operating systems out of the same codebase. Follow the OS specific instructions from below.

#### Linux
```shell
git clone https://github.com/komodoplatform/komodo --branch master --single-branch
cd komodo
./zcutil/fetch-params.sh
# -j8 = using 8 threads for the compilation - replace 8 with number of threads you want to use
./zcutil/build.sh -j8
#This can take some time.
```

>>>>>>> upstream/master

#### OSX
Ensure you have [brew](https://brew.sh) and Command Line Tools installed.
```shell
# Install brew
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
# Install Xcode, opens a pop-up window to install CLT without installing the entire Xcode package
xcode-select --install 
# Update brew and install dependencies
brew update
brew upgrade
brew tap discoteq/discoteq; brew install flock
brew install autoconf autogen automake
brew update && brew install gcc@8
brew install binutils
brew install protobuf
brew install coreutils
brew install wget
# Clone the Komodo repo
git clone https://github.com/komodoplatform/komodo --branch master --single-branch
# Change master branch to other branch you wish to compile
cd komodo
./zcutil/fetch-params.sh
# -j8 = using 8 threads for the compilation - replace 8 with number of threads you want to use
./zcutil/build-mac.sh -j8
# This can take some time.
```


**Komodo is unfinished and highly experimental, use at your own risk.**


Building
--------
Build Zcash along with most dependencies from source by running
`./zcutil/build.sh`. Currently only Linux is officially supported.
=======
#### Windows
Use a debian cross-compilation setup with mingw for windows and run:
```shell
sudo apt-get install build-essential pkg-config libc6-dev m4 g++-multilib autoconf libtool ncurses-dev unzip git python python-zmq zlib1g-dev wget libcurl4-gnutls-dev bsdmainutils automake curl cmake mingw-w64
curl https://sh.rustup.rs -sSf | sh
source $HOME/.cargo/env
rustup target add x86_64-pc-windows-gnu
git clone https://github.com/jl777/komodo --branch master --single-branch
cd komodo
./zcutil/fetch-params.sh
# -j8 = using 8 threads for the compilation - replace 8 with number of threads you want to use
./zcutil/build-win.sh -j8
#This can take some time.
```
**komodo is experimental and a work-in-progress.** Use at your own risk.

To reset the Komodo blockchain change into the *~/.komodo* data directory and delete the corresponding files by running `rm -rf blocks chainstate debug.log komodostate db.log`

#### Create komodo.conf

Create a komodo.conf file:

```
mkdir ~/.komodo
cd ~/.komodo
touch komodo.conf

#Add the following lines to the komodo.conf file:
rpcuser=yourrpcusername
rpcpassword=yoursecurerpcpassword
rpcbind=127.0.0.1
txindex=1
addnode=5.9.102.210
addnode=78.47.196.146
addnode=178.63.69.164
addnode=88.198.65.74
addnode=5.9.122.241
addnode=144.76.94.38
addnode=89.248.166.91
```
### Create your own Blockchain based on Komodo

Komodo allows anyone to create a runtime fork which represents an independent Blockchain. Below are the detailed instructions:
Setup two independent servers with at least 1 server having a static IP and build komodod on those servers.  

#### On server 1 (with static IP) run:
```shell
./komodod -ac_name=name_of_your_chain -ac_supply=100000 -bind=ip_of_server_1 &
```

#### On server 2 run:
```shell
./komodod -ac_name=name_of_your_chain -ac_supply=100000 -addnode=ip_of_server_1 -gen &
```

**Komodo is based on Zcash which is unfinished and highly experimental.** Use at your own risk.


**NOTE TO EXCHANGES:**
https://bitcointalk.org/index.php?topic=1605144.msg17732151#msg17732151
There is a small chance that an outbound transaction will give an error due to mismatched values in wallet calculations. There is a -exchange option that you can run komodod with, but make sure to have the entire transaction history under the same -exchange mode. Otherwise you will get wallet conflicts.

**To change modes:**

a) backup all privkeys (launch komodod with `-exportdir=<path>` and `dumpwallet`)  
b) start a totally new sync including `wallet.dat`, launch with same `exportdir`  
c) stop it before it gets too far and import all the privkeys from a) using `komodo-cli importwallet filename`  
d) resume sync till it gets to chaintip  

For example:
```shell
./komodod -exportdir=/tmp &
./komodo-cli dumpwallet example
./komodo-cli stop
mv ~/.komodo ~/.komodo.old && mkdir ~/.komodo && cp ~/.komodo.old/komodo.conf ~/.komodo.old/peers.dat ~/.komodo
./komodod -exchange -exportdir=/tmp &
./komodo-cli importwallet /tmp/example
```
---


License
-------
For license information see the file [COPYING](COPYING).
=======

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
>>>>>>> upstream/master

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
