# <img src="https://github.com/lneuhaus/pyrpl/blob/master/logo.png" width="250" alt="PyRPL">
![travis status](https://travis-ci.com/lneuhaus/pyrpl.svg?token=Au8JgYk93p9iq2p6bSTp&branch=master "Travis status")

PyRPL (Python RedPitaya Lockbox) turns your RedPitaya into a powerful DSP device, especially suitable as a digital lockbox and measurement device in quantum optics experiments.


## Installation
Make sure you have an installation of Python (2 or 3), preferrably Anaconda.
Make sure you have a working installation of the python packages [Numpy](http://www.numpy.org/) (with ```conda install numpy```) and [PyQt4](https://pypi.python.org/pypi/PyQt4) (with ```conda install pyqt=4```). 

Download and extract or clone (with ```git clone https://github.com/lneuhaus/pyrpl.git```) the pyrpl repository to your computer. Install PyRPL by navigating with a command line terminal into the pyrpl root directory and typing
```
python setup.py develop
```

## Quick start
First, hook up your Red Pitaya / STEMlab to a LAN accessible from your computer (follow the instructions for this on redpitya.com and make sure you can access your Red Pitaya in your web browser by typing its ip-address / hostname into the address bar).
In an IPython console or JuPyter notebook, type
```
from pyrpl import Pyrpl
p = Pyrpl(hostname='your_redpitaya_ip_address')
```
The GUI should open and you can start playing around with it.

## Next steps
You can find all documentation in the subfolder ["doc"](https://github.com/lneuhaus/pyrpl/blob/master/doc). Get started by reading our paper on PyRPL, reading the official [html documentation](https://github.com/lneuhaus/pyrpl/blob/master/doc/sphinx/build/html/index.html), or going through the [tutorial.ipynb](https://github.com/lneuhaus/pyrpl/blob/master/doc/tutorial.ipynb) notebook. 

## Updates
Since PyRPL is continuously improved, you should install upgrades if you expect bugfixes by navigating into the pyrpl root directory on your local harddisk computer and typing
```
git pull
```

## Issues
Please report any problems or wishes as a new issue on [this page](https://github.com/lneuhaus/pyrpl/issues).

## License
Please read our license file [LICENSE](https://github.com/lneuhaus/pyrpl/blob/master/LICENSE) for more information. 
