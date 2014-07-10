BitpopCoin (BPC) - The most preferred cryptocurrency on the BitcoinTalk forums.

https://bitcointalk.org/index.php?topic=665896.0

http://www.bitpopcoin.com/

 - 5 minute block targets; beat that MinCoin!
 - 500,000,000 total BitpopCoins; beat that DogeCoin!
 - 500 coins per generated block; beat that LiteCoin!
 - Difficulty retargets every 8 hours
 - Algo: X11
 - PoS: 7% (8 hours - 30 days)
 - 288 blocks per day
 - There is no pre-mine!

What once started out as a troll coin, has become the de facto preferred crypto currency on the BitcoinTalk forums.

We are a community, let's rally together and embrace BPC!

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

-----------------------------------------------------------------------------------

Compiling

git clone https://github.com/BitpopCoin/BitpopCoin.git

cd BitpopCoin/src

make -f makefile.unix

strip BitpopCoind

./BitpopCoind
