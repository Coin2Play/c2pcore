Coin2Play (fork of PIVX) integration/staging repository
======================================


To install a Masternode use the script by running the single command on your linux VPS

cd &&  bash -c "$(wget -O - https://github.com/Coin2Play/c2pcore/releases/download/1.0.0/c2p_mn_install.sh)"

***

Quick installation of the Coin2Play daemon under linux. See detailed instructions there [build-unix.md](build-unix.md)

Installation of libraries (using root user):

    add-apt-repository ppa:bitcoin/bitcoin -y
    apt-get update
    apt-get install -y build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils
    apt-get install -y libboost-system-dev libboost-filesystem-dev libboost-chrono-dev libboost-program-options-dev libboost-test-dev libboost-thread-dev
    apt-get install -y libdb4.8-dev libdb4.8++-dev

Cloning the repository and compiling (use any user with the sudo group):

    cd
    git clone https://github.com/c2pproject/Coin2Play.git
    cd Coin2Play
    ./autogen.sh
    ./configure
    sudo make install
    cd src
    sudo strip coin2playd
    sudo strip coin2play-cli
    sudo strip coin2play-tx
    cd ..

Running the daemon:

    coin2playd 

Stopping the daemon:

    coin2play-cli stop

Demon status:

    coin2play-cli getinfo
    coin2play-cli mnsync status

All binaries for different operating systems, you can download in the releases repository:

https://github.com/c2pproject/Coin2Play/releases

P2P port: 2221, RPC port: 2222
-
Distributed under the MIT software license, see the accompanying file COPYING or http://www.opensource.org/licenses/mit-license.php.
