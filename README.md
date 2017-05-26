# FreeSWITCH_install_ubuntu
instruction for installing the freeswitch on ubuntu syste,

# step 1: 
apt-get update
# step 2:
apt-get upgrade
# step 3:
apt-get install build-essential subversion automake autoconf wget  libtiff5-dev libtool   \   
libncurses5-dev git-core libcurl4-openssl-dev libjpeg-dev                              \
unixodbc-dev unixodbc flex bison build-essential openssl bison flex perl libdbi-perl \           
libdbd-pg-perl libfrontier-rpc-perl libterm-readline-gnu-perl libberkeleydb-perl  \
libpcre3-dev libxml2-dev libpcre3 libxml2 perl libdbi-perl  libfrontier-rpc-perl   \          
libterm-readline-gnu-perl libberkeleydb-perl pkg-config sqlite3 libsqlite3-dev libspeex-dev  \
libspeexdsp-dev libldns-dev  libedit-dev libvpx-dev yasm nasm

# step 4:
git clone –b v1.6 https://freeswitch.org/stash/scm/fs/freeswitch.git freeswitch.git

# step 5:
cd freeswitch

# step 6
./bootstrap.sh

# step 7 
./configure && make && make install

## Enjoy FreeSWITCH on ubuntu system
