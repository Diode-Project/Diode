Diode
====

Diode "DIO" the X13 PoW/PoS Cryptocurrency.

Algorithm: X13 POW/POS

Ticker: DIO

Current Version "1.0.0.0"

Max Coins: 4,500,000 DIO
RPC Port: 29875
P2P Port: 29874
30 Blocks to Mature
Block Reward Schedule:

Block 1 is 50,000  DIO

Block 2-3000 are 1500 DIO

PoS Start: Block 2800
PoS Interest: 5%

==========================================================

Daemon Build Instructions:

git clone https://github.com/DiodeCoin/Diode.git

cd Diode/src

mkdir obj

chmod +x leveldb/build_detect_platform

make -f makefile.unix
