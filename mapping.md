# WIPPS Parameter names mapping

## Surface parameters

### 2-m temperature

ECMWF shortname: [2t](https://codes.ecmwf.int/grib/param-db/167)

CF-name: [air_temperature](https://vocab.nerc.ac.uk/standard_name/air_temperature/)

### 2-m minimum and maximum temperatures in the last 3-hour/6-hour period

ECMWF shortname: [mx2t3](https://codes.ecmwf.int/grib/param-db/228026), [mn2t3](https://codes.ecmwf.int/grib/param-db/228027), [mx2t6](https://codes.ecmwf.int/grib/param-db/121), [mn2t6](https://codes.ecmwf.int/grib/param-db/122)

CF-name: [air_temperature](https://vocab.nerc.ac.uk/standard_name/air_temperature)

### 2-m dewpoint temperature

ECMWF shortname: [2d](https://codes.ecmwf.int/grib/param-db/168)

CF-name: [dew_point_temperature](http://vocab.nerc.ac.uk/standard_name/dew_point_temperature/)

### 10-m u, 10-m v

ECMWF shortname: [u_10m](https://codes.ecmwf.int/grib/param-db/500027), [v_10m](https://codes.ecmwf.int/grib/param-db/500029)

CF-name: [x_wind](http://vocab.nerc.ac.uk/standard_name/x_wind/), [y_wind](https://vocab.nerc.ac.uk/standard_name/y_wind/)

### 10-m wind gust

Wind gust is the maximum gust in the last 3-hour or 6-hour period.

ECMWF shortname: [10fg3](https://codes.ecmwf.int/grib/param-db/228028), [10fg6](https://codes.ecmwf.int/grib/param-db/123)

CF-name: [wind_speed_of_gust](https://vocab.nerc.ac.uk/standard_name/wind_speed_of_gust/)

### Total precipitation

ECMWF shortname: [tp](https://codes.ecmwf.int/grib/param-db/228)

CF-name: [precipitation_amount](https://vocab.nerc.ac.uk/standard_name/precipitation_amount/)

### Total solid precipitation

Water equivalent of total solid precipitation is the combination of snow and graupel (ice pellets) (where available); snow and graupel can be provided as two separate parameters

ECMWF shortname: [titspf](https://codes.ecmwf.int/grib/param-db/260645)

CF-name: [solid_precipitation_flux](https://vocab.nerc.ac.uk/standard_name/solid_precipitation_flux/)

### CAPE

CAPE: Convective Available Potential Energy. Provision of the most unstable CAPE (MUCAPE) is recommended. RSMCs are required to provide information, on the model characteristics web page, as to which type of CAPE is provided.

ECMWF shortname: [cape](https://codes.ecmwf.int/grib/param-db/59)

CF-name: [atmosphere_convective_available_potential_energy](https://vocab.nerc.ac.uk/standard_name/atmosphere_convective_available_potential_energy/)

### Total precipitable water

ECMWF shortname:
ECMWF link:
CF-name:
CF-link:

### Total cloud cover

ECMWF shortname: [tcc](https://codes.ecmwf.int/grib/param-db/164)

CF-name: [cloud_area_fraction](https://vocab.nerc.ac.uk/standard_name/cloud_area_fraction/
)

## Level parameters

### Geopotential height

Level: 850/500/250/200 hPa

ECMWF shortname: [gh](https://codes.ecmwf.int/grib/param-db/156)

CF-name: [geopotential_height](https://vocab.nerc.ac.uk/standard_name/geopotential_height/)

### Temperature

Level: 850/500/250/200 hPa

ECMWF shortname: [t](https://codes.ecmwf.int/grib/param-db/130)

CF-name: [air_temperature](https://vocab.nerc.ac.uk/standard_name/air_temperature/
)

### Wind zonal velocity (u) and meridional velocity (v)

Level: 925/850/700/500/250/200 hPa

ECMWF-shortname:

CF-name:

### Relative humidity

Level: 850/700/500/200 hPa

ECMWF shortname: [r](https://codes.ecmwf.int/grib/param-db/157)

CF-name: [relative_humidity](https://vocab.nerc.ac.uk/standard_name/relative_humidity/)
