[BPC] BitpopCoin - A coin for the community, brought to you by a Hero Member.

https://bitcointalk.org/index.php?topic=665896.0

http://www.bitpopcoin.com/


 - 5 minute block targets
 - 500,000,000 total BitpopCoins
 - 500 coins per generated block
 - Difficulty retargets after every block
 - Algorithm: X11
 - PoS: 7% (8 hours - 30 days)
 - 288 blocks per day
 - There is no pre-mine!
 - Not Scrypt, ASIC resistant!
 - Launched on July 8, 2014.


Donate: BSeyCRUHrr2Mi5RmzZkm21Q963LCH2x2bF

-----------------------------------------------------------------------------------

bitpopcoin.conf

server=1

listen=1

daemon=1

rpcuser=bitpop

rpcpassword=bitpop

rpcport=45437

port=45438

rpcallowip=127.0.0.1

dns=1

maxconnections=32

upnp=1

addnode=node.bitpopcoin.com

addnode=node2.bitpopcoin.com

addnode=altpooler.com:19013

-----------------------------------------------------------------------------------

Compiling

git clone https://github.com/BitpopCoin/BitpopCoin.git

cd BitpopCoin/src

make -f makefile.unix

strip BitpopCoind

./BitpopCoind

./BitpopCoind getinfo
