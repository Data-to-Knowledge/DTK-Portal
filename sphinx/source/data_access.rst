Data Access Tools
=================

This section lists the projects that have a primary emphasis on data access to data systems.

nasadap
-------
The `nasadap <https://github.com/mullenkamp/nasadap>`_ package was created to provide easy access to NASA satellite data via their OPeNDAP servers and convert them to `xarray <http://xarray.pydata.org>`_ datasets. At the moment, only precipitation data from the TRMM and GPM missions are available. It uses the python package `pydap <https://pydap.readthedocs.io>`_ to access the OPeNDAP servers.

pyhydllp
------------
The `pyhydllp <https://pyhydllp.readthedocs.io>`_  project was created to develop a Python API to the Hydstra program (`Kisters <http://kisters.com.au>`_) via the hydllp.dll provided by Hydstra. It includes many of the functions for accessing time series data in Hydstra.

hilltop-py
----------
The `hilltop-py <https://hilltop-py.readthedocs.io>`_ project was created to create python wrappers for the various programmatic APIs of `Hilltop <http://www.hilltop.co.nz/>`_. The existing access methods are via the windows COM, directly via the new Hilltop Python API, and via the Hilltop web service.

pyhydrotel
----------
The `pyhydrotel <https://github.com/mullenkamp/pyhydrotel>`_ project was created to provide a set of functions to be able extract time series data stored in a hydrotel MS sql database.
