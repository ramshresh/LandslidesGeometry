GDAL INSTALLATION

CREATE VIRTUALENV
python -m virtualenv env


INSPECT python version
(env) C:\Dev\django-desinventar-server>python
Python 3.10.1 (tags/v3.10.1:2cd268a, Dec  6 2021, 19:10:37) [MSC v.1929 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>>

link to download gdal wheels
https://www.lfd.uci.edu/~gohlke/pythonlibs/#gdal

pip install GDAL-3.4.1-cp310-cp310-win_amd64.whl



TROUBLESHOOT:
PROBLEM: 

>>> from osgeo import gdal
ERROR 1: Can't load requested DLL: C:\Program Files\GDAL\gdalplugins\gdal_BAG.dll
127: The specified procedure could not be found.

ERROR 1: Can't load requested DLL: C:\Program Files\GDAL\gdalplugins\gdal_BAG.dll
127: The specified procedure could not be found.

ERROR 1: Can't load requested DLL: C:\Program Files\GDAL\gdalplugins\gdal_FITS.dll
127: The specified procedure could not be found.

ERROR 1: Can't load requested DLL: C:\Program Files\GDAL\gdalplugins\gdal_FITS.dll
127: The specified procedure could not be found.

ERROR 1: Can't load requested DLL: C:\Program Files\GDAL\gdalplugins\gdal_GMT.dll
127: The specified procedure could not be found.

ERROR 1: Can't load requested DLL: C:\Program Files\GDAL\gdalplugins\gdal_GMT.dll
127: The specified procedure could not be found.

ERROR 1: Can't load requested DLL: C:\Program Files\GDAL\gdalplugins\gdal_HDF4.dll
127: The specified procedure could not be found.

ERROR 1: Can't load requested DLL: C:\Program Files\GDAL\gdalplugins\gdal_HDF4.dll
127: The specified procedure could not be found.

ERROR 1: Can't load requested DLL: C:\Program Files\GDAL\gdalplugins\gdal_HDF4Image.dll
127: The specified procedure could not be found.

ERROR 1: Can't load requested DLL: C:\Program Files\GDAL\gdalplugins\gdal_HDF4Image.dll
127: The specified procedure could not be found.

ERROR 1: Can't load requested DLL: C:\Program Files\GDAL\gdalplugins\gdal_HDF5.dll
127: The specified procedure could not be found.

ERROR 1: Can't load requested DLL: C:\Program Files\GDAL\gdalplugins\gdal_HDF5.dll
127: The specified procedure could not be found.

ERROR 1: Can't load requested DLL: C:\Program Files\GDAL\gdalplugins\gdal_HDF5Image.dll
127: The specified procedure could not be found.

ERROR 1: Can't load requested DLL: C:\Program Files\GDAL\gdalplugins\gdal_HDF5Image.dll
127: The specified procedure could not be found.

ERROR 1: Can't load requested DLL: C:\Program Files\GDAL\gdalplugins\gdal_KEA.dll
127: The specified procedure could not be found.

ERROR 1: Can't load requested DLL: C:\Program Files\GDAL\gdalplugins\gdal_KEA.dll
127: The specified procedure could not be found.

ERROR 1: Can't load requested DLL: C:\Program Files\GDAL\gdalplugins\gdal_netCDF.dll
127: The specified procedure could not be found.

ERROR 1: Can't load requested DLL: C:\Program Files\GDAL\gdalplugins\gdal_netCDF.dll
127: The specified procedure could not be found.

ERROR 1: Can't load requested DLL: C:\Program Files\GDAL\gdalplugins\ogr_MSSQLSpatial.dll
126: The specified module could not be found.

ERROR 1: Can't load requested DLL: C:\Program Files\GDAL\gdalplugins\ogr_MSSQLSpatial.dll
126: The specified module could not be found.

SOLUTION:
[1]: https://gis.stackexchange.com/questions/321693/dll-error-in-various-gdal-installations/368325
