# Identity-Wallet

BUILDING WALLET

On Linux ubuntu 14.4 

make sure to install QT with :

--> sudo apt-get install qt5-default
--> sudo apt install cmake-qt-gui


(make sure your folder for currency is named cryptonote)

for example have a folder named Identity, inside you have cryptonote, and its contents identity/cryptonote

from your identity folder open terminal and use:

-->git clone https://github.com/IdentityProject/Identity-Wallet.git identitywallet

and

-->git clone https://github.com/fukuchi/libqrencode.git

the second repository is the QR generator for private key

next

You need all three directories or folders (cryptonote,libqrencode,identitywallet)in the same place, or in the same folder E.G /identity/

change directory use:

--> cd identitywallet

Now you need to create a link with some folders use:

--> ln -s ../cryptonote cryptonote

--> ln -s ../libqrencode libqrencode

now that you have done that youre ready to compile use:

--> mkdir build && cd build && cmake ..&&make

we its done goto /identitywallet/build

run identity executable

Youre wallet is ready.
