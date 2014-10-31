BOOM
====

BoomCoin "BOOM" the X13 PoW/PoS Cryptocurrency.

Algorithm: X13 POW/POS

Ticker: BOOM

Current Version "3.0.0.0"

Max Coins: 16,000,000 BOOM

RPC Port: 28266

30 Blocks to mature

1 minute block time

Block Reward Schedule:

Block 1 is 11,380,000  BOOM (SWAP BLOCK)

Block 2 - 43,200 are 25 BOOM (30 days of mining)

X13 -(blake, bmw, groestl, jh, keccak, skein, luffa, cubehash, shavite, simd, echo, hamsi, fugue)

More info can be found at:

Website - http://cleverhash.com

Bitcointalk - https://bitcointalk.org/index.php?topic=716699.0


==========================================================

Daemon Build Instructions:

git clone https://github.com/Cleverhash/BOOM.git

cd BOOM/src

mkdir obj

chmod +x leveldb/build_detect_platform

make -f makefile.unix
