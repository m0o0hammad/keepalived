############################install keepalived latest############################

yum install curl gcc openssl-devel libnl3-devel net-snmp-devel

curl --progress https://www.keepalived.org/software/keepalived-2.1.2.tar.gz | tar xz

cd keepalived-1.2.15

./configure

make

sudo make install

./configure --prefix=/usr/local/keepalived-2.1.2

###################################################################################
