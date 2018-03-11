# python-setup
pymc3

## setup python under VirtualBox-Linux
PyMC3 works fine under Linux 16.04

https://www.anaconda.com/downloads

install anaconda 2.7

conda install pymc3

pip install patsy pandas

export MKL_THREADING_LAYER=GNU

jupyter notebook


## Windows 10 / Linux Subsystem on Windows

https://www.anaconda.com/downloads

install anaconda 2.7 or 3.x

### fix the openssl issue

sudo apt install execstack

cd ~/anaconda3/lib

execstack -c libcrypto.so.1.0.0

conda install pymc3 pandas patsy

### install compiler

sudo apt update

sudo apt install build-essential

### add environment variable to .bashrc

export MKL_THREADING_LAYER=GNU

### start jupter in LSW

jupyter notebook
