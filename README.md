## TESTNET ONLY REPO

### Installation for Linux from source

There are two CureCoin Linux based clients that you can compile for yourself: one with a nice graphical interface, and one that operates entirely in the command-line. The first is highly recommended and is a good choice for most users, but expert users may prefer the command-line (headless) client instead. The GUI client is known as "curecoin-qt" and the headless client is called "curecoind". Installing either one or both is extremely simple. Just follow these directions:

* **Install from source**

  This involves downloading the source, meeting the dependencies, compiling the code, and then installing the resulting software. 

   git clone https://github.com/ReikiLVL3/CurecoinSource.git

    FOR THE GUI CLIENT:

    > 1. **sudo apt-get install qt5-default qt5-qmake qtbase5-dev-tools qttools5-dev-tools libboost-dev libboost-system-dev libboost-filesystem-dev libboost-program-options-dev libboost-thread-dev libssl-dev libminiupnpc-dev libdb5.3++-dev dh-make build-essential**
    > 2. From the main directory, run the following:
    > 3. **qmake && make**

    FOR THE HEADLESS CURECOIND:

    > 1. **sudo apt-get install libboost-all-dev libqrencode-dev libssl-dev libdb5.3-dev libdb5.3++-dev libminiupnpc-dev dh-make build-essential**
    > 2. **cd src**
    > 3. **make -f makefile.unix**
    > 4. **sudo make install** Alternatively, don't run that command and just place the binary wherever you want.

    On new versions of linux such a Ubuntu 18.04 or Debain 9 + "sudo apt-get install libssl1.0-dev". Use libdb4.8 or libdb5.1 on older linux versions (IE 14.04). Ubuntu 16.04 use need libdb5.3++-dev. 

### Reporting bugs or getting assistance

General help for CureCoin can be found on the forums at https://www.curecoin.net/forum or on Discord https://discord.gg/jtztkFZ . The forum is recommended for non frequent users of irc. 
