# JinCoin
cbd106's bitcoin to our laboratory
a fork project from bitcoin 


## operating process

./autogen.sh

./configure LDFLAGS="-L/home/ubuntu/JinCoin/db6/lib/" CPPFLAGS="-I/home/ubuntu/JinCoin/db6/include/" --with-incompatible-bdb

sudo make

sudo make install
