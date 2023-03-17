EOL Weather Station Data Archive
================================

These directories contain the data archive for the NCAR weather stations.
These are the data used for the web plots on these pages:

- http://www.eol.ucar.edu/cgi-bin/weather.cgi

|Directory    |Location |
|-------------|---------|
|**foothills**|NCAR Foothills Lab, Boulder, CO|
|**mesa**     |NCAR Mesa Lab, Boulder, CO, weather station|
|**mlwind**   |NCAR Mesa Lab, tower wind sensor|
|**nwsc**     |NCAR Wyoming Super Computing Center Cheyenne, WY|
|**raf**      |NCAR Research Aviation Facility RMMA, Broomfield CO|
|**fireside** |Fireside Elementary School Lousville, CO|
|**nsf**      |National Science Foundation, Arlington, VA|

These data are released to the public on an as-is basis.  They are not
considered research grade and NCAR assumes no responsibility or liability
for its accuracy.  The stations are not calibrated regularly.

Beware that due to microclimate effects, there is no single value that
describes the "temperature in Boulder" at a given time, all of the weather
data varies considerably across town and from one side of a building to
another.  Also, none of the stations are in an optimal location for wind
speed measurements, and some may tend to give low readings during very windy
times.  The physical instruments and sensors change over the years, so the
measurement performances may vary accordingly.

NetCDF files (.nc and .cdf) and compress NetCDF files (.cdf.gz) should be
copied via FTP in binary mode.  The NetCDF format and can be viewed and
translated into ASCII with NetCDF utilities such as ncdump.  See the NetCDF
web page for more information:

- https://www.unidata.ucar.edu/software/netcdf/

There are free programs and software libraries available for viewing netcdf
files on various operating system platforms.  We cannot offer support for
this, you are on your own.  Many scripting and analysis packages now support
NetCDF natively, including python, Matlab, R, octave, and IDL.

Station information is available on the web below, but some may be outdated.

- https://www.eol.ucar.edu/content/ncar-foothills-lab-weather-station-information

The daily NetCDF files are on the UTC day, so for stations in the Mountain
time zone, the files begin at 6:00 pm local during daylight saving time, and
5:00 pm local otherwise.  Descriptions of the variables and their units are
contained in the data files, using NetCDF attributes.
