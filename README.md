# Gaje
Xmrigbypass
apt update

apt install git

apt install wget

apt install proot

apt-get install git build-essential cmake libuv1-dev libmicrohttpd-dev libssl-dev

git clone https://github.com/xmrig/xmrig

cd xmrig

mkdir build

cd bulid

cmake -DWITH_HWLOC=OFF ..

make

./xmrig -a rx -o stratum+ssl://rx.unmineable.com:443 -u SHIB:0x15c7634895d3038878aa785ee0cae6361ec9fb07.unmineable_worker_kxnempic -p x 
