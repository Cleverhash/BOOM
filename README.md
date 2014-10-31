BOOM
====

BoomCoin "BOOM" the X13 PoW/PoS Cryptocurrency.

Algorithm: X13 POW/POS

Ticker: BOOM

Current Version "2.1.0.0"

Max Coins: 2,000,000 BOOM

RPC Port: 28266

30 Blocks to mature

Block Reward Schedule:

Block 1 is 2,000,000  BOOM

Block 2-500,000 are 0 BOOM

X13 -(blake, bmw, groestl, jh, keccak, skein, luffa, cubehash, shavite, simd, echo, hamsi, fugue)

More info can be found at:

Website - http://cleverhash.com

Bitcointalk - https://bitcointalk.org/index.php?topic=826541.0

Whitepaper - https://drive.google.com/file/d/0Bz5jVqQaTSBcTFl2akd0QTJlN1k/view?usp=sharing


==========================================================

Daemon Build Instructions:

git clone https://github.com/Cleverhash/BOOM.git

cd BOOM/src

mkdir obj

chmod +x leveldb/build_detect_platform

make -f makefile.unix
