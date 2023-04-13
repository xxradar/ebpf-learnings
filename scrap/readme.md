1. Install ubuntu box on AWs
2. Install tooling
```
sudo -s
apt-get update-y make gcc libelf-dev
```
```
git clone --recurse-submodules https://github.com/lizrice/learning-ebpf
cd learning-ebpf
cd libbpf/src
make install 
```
```
cd ~
git clone --recurse-submodules https://github.com/libbpf/bpftool.git
cd bpftool/src 
make install 
```
