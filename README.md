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


## Windows PC / LSW

https://www.anaconda.com/downloads

install anaconda 2.7 or 3.x

#fix the openssl issue

sudo apt install execstack

cd ~/anaconda3/lib

execstack -c libcrypto.so.1.0.0


conda install -c conda-forge pymc3

pip install patsy pandas

export MKL_THREADING_LAYER=GNU

jupyter notebook
