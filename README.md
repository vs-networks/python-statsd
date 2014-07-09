How to create a distribution file:

	Update statsd/__init__.py with correct version.
	Run python setup.py sdist
	Upload to files:
		scp dist/python-statsd-1.6.3.vsn-01.tar.gz files:/nas/web/internal/pylibs
