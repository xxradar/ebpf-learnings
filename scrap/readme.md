1. Install ubuntu box on AWs
2. Install tooling
```
sudo -s
apt-get update
apt install make
apt install gcc
apt-get install libelf-dev
```
```
cd libbpf/src
make install 
```
```
cd ~
git clone --recurse-submodules https://github.com/libbpf/bpftool.git
cd bpftool/src 
make install 
```
