<p align="center">
	<b>pypi XML-RPC wrapper</b>
</p>

<p>
	<a href="https://travis-ci.org/b'russianidiot'/pypixmlrpc.py" class="reference external">
		<img src="https://travis-ci.org/b'russianidiot'/pypixmlrpc.py.svg?branch=master" alt="Build Status">
	</a>
	<!--
	<a href="https://codecov.io/github/b'russianidiot'/pypixmlrpc.py/">
		<img src="https://img.shields.io/codecov/c/github/b'russianidiot'/pypixmlrpc.py.svg" alt="Codecov">
	</a>
	-->
</p>
<p>
	<a href="http://badge.fury.io/py/pypixmlrpc" class="reference external">
		<img src="https://badge.fury.io/py/pypixmlrpc.svg" alt="PyPI version">
	</a>
	<a href="https://pypi.python.org/pypi/pypixmlrpc">
		<img src="https://img.shields.io/pypi/pyversions/pypixmlrpc.svg" alt="PyPI">
	</a>

</p>

	
Install
-------

[github.com](http://github.com/b'russianidiot'/pypixmlrpc.py):
`pip install git+git://github.com/b'russianidiot'/pypixmlrpc.py.git`

[pypi.python.org](https://pypi.python.org): `pip install pypixmlrpc`

[download](https://github.com/b'russianidiot'/pypixmlrpc.py/archive/master.zip): `python setup.py install` or `setup/.setup.py develop.command` 

	

	

Usage 
=====
```
from pypixmlrpc import *

pypi.list_packages()

pypi.user_packages("kennethreitz")

pypi.package_releases("requests")

pypi.package_roles("requests")

version="x.y.z"
pypi.release_data("requests",version)
pypi.release_downloads("requests",version)
pypi.release_urls("requests",version)
```

---

**Tested**: python 2.6, 2.7, 3+

---

<p align="center">
my Python packages 
<a href="http://b'russianidiot'.github.io/python/packages">b'russianidiot'.github.io/python/packages</a> <img src="http://b'russianidiot'.github.io/images/python/16.png" />
</p>
<p align="center">
my Python repos <a href="http://b'russianidiot'.github.io/python/">b'russianidiot'.github.io/python/</a>
<img src="http://b'russianidiot'.github.io/images/python/16.png" />
</p>

<p align="center">
	all repos <a href="http://b'russianidiot'.github.io/">b'russianidiot'.github.io</a> <img src="http://b'russianidiot'.github.io/images/star/16.png" />
</p>

<p align="center">
	README.md generated with <a href="https://github.com/b'russianidiot'/README.mako.py.automation">README.mako.py.automation</a> + <a href="https://github.com/b'russianidiot'/.README.mako">.README.mako</a> 
<img src="http://b'russianidiot'.github.io/images/book/16.png">
</p>

<p align="center">
	follow me <a href="http://github.com/b'russianidiot'">github.com/b'russianidiot'</a>
<img src="http://b'russianidiot'.github.io/images/github/16.png" />
</p>