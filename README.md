======================================
[CompCube](http://www.cs.kumamoto-u.ac.jp/~yasuko/)
======================================

Author:    Yasuko Matsubara 

Created:   2016-05-14

------------
Introduction
------------

This is a python code of "CompCube"

------------
Quick demo
------------

	(a) Interactive demo (product-related keywords)
        	$ make demo
	(b) Fitting data
        	$ make fit

------------
Installation
------------

python settings: 
	You might need to install "lmfit" and "sklearn", 
 - lmfit (for fit.py): 
	$ git clone git://github.com/lmfit/lmfit-py
	$ sudo python setup.py install
 - sklearn (for fastica, ica.py):
    $ git clone git://github.com/scikit-learn/scikit-learn
    $ sudo python setup.py install


------------
Datasets
------------

See `./_dat/`

------------
References
------------

Please see, 
Yasuko Matsubara, Yasushi Sakurai, Christos Faloutsos, 
"Non-Linear Mining of Competing Local Activities", WWW 2016.

------------
Updates
------------

Version: 5-15-2016
    - released


