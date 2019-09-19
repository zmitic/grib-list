To extra all available grib types, download one grib file first. Convert it to CSV without any filtering like this:

```
wgrib2 "2019-09-05 06:00:00.grb" -csv test.csv
```

At this moment, these are available types:

```
4LFTX:surface
5WAVH:500 mb
ABSV:10 mb = Absolute Vorticity [1/s]
ABSV:100 mb = Absolute Vorticity [1/s]
ABSV:1000 mb = Absolute Vorticity [1/s]
ABSV:150 mb
ABSV:20 mb
ABSV:200 mb
ABSV:250 mb
ABSV:30 mb
ABSV:300 mb
ABSV:350 mb
ABSV:400 mb
ABSV:450 mb
ABSV:50 mb
ABSV:500 mb
ABSV:550 mb
ABSV:600 mb
ABSV:650 mb
ABSV:70 mb
ABSV:700 mb
ABSV:750 mb
ABSV:800 mb
ABSV:850 mb
ABSV:900 mb
ABSV:925 mb
ABSV:950 mb
ABSV:975 mb
APTMP:2 m above ground
CAPE:180-0 mb above ground
CAPE:255-0 mb above ground
CAPE:surface
CIN:180-0 mb above ground
CIN:255-0 mb above ground
CIN:surface
CLMR:100 mb
CLMR:1000 mb
CLMR:150 mb
CLMR:200 mb
CLMR:250 mb
CLMR:300 mb
CLMR:350 mb
CLMR:400 mb
CLMR:450 mb
CLMR:500 mb
CLMR:550 mb
CLMR:600 mb
CLMR:650 mb
CLMR:700 mb
CLMR:750 mb
CLMR:800 mb
CLMR:850 mb
CLMR:900 mb
CLMR:925 mb
CLMR:950 mb
CLMR:975 mb
CPOFP:surface
CWAT:entire atmosphere (considered as a single layer)
DPT:2 m above ground
FLDCP:surface
GUST:surface
HGT:0C isotherm
HGT:1 mb
HGT:10 mb
HGT:100 mb
HGT:1000 mb
HGT:150 mb
HGT:2 mb
HGT:20 mb
HGT:200 mb
HGT:250 mb
HGT:3 mb
HGT:30 mb
HGT:300 mb
HGT:350 mb
HGT:400 mb
HGT:450 mb
HGT:5 mb
HGT:50 mb
HGT:500 mb
HGT:550 mb
HGT:600 mb
HGT:650 mb
HGT:7 mb
HGT:70 mb
HGT:700 mb
HGT:750 mb
HGT:800 mb
HGT:850 mb
HGT:900 mb
HGT:925 mb
HGT:950 mb
HGT:975 mb
HGT:PV=-2e-06 (Km^2/kg/s) surface
HGT:PV=2e-06 (Km^2/kg/s) surface
HGT:highest tropospheric freezing level
HGT:max wind
HGT:surface
HGT:tropopause
HINDEX:surface
HLCY:3000-0 m above ground
HPBL:surface
ICAHT:max wind
ICAHT:tropopause
ICEC:surface
LAND:surface
LANDN:surface
LFTX:surface
MSLET:mean sea level
O3MR:1 mb
O3MR:10 mb
O3MR:100 mb
O3MR:150 mb
O3MR:2 mb
O3MR:20 mb
O3MR:200 mb
O3MR:250 mb
O3MR:3 mb
O3MR:30 mb
O3MR:300 mb
O3MR:350 mb
O3MR:400 mb
O3MR:5 mb
O3MR:50 mb
O3MR:7 mb
O3MR:70 mb
PLPL:255-0 mb above ground
POT:0.995 sigma level
PRES:80 m above ground
PRES:PV=-2e-06 (Km^2/kg/s) surface
PRES:PV=2e-06 (Km^2/kg/s) surface
PRES:max wind
PRES:surface
PRES:tropopause
PRMSL:mean sea level
PWAT:entire atmosphere (considered as a single layer)
RH:0.33-1 sigma layer
RH:0.44-0.72 sigma layer
RH:0.44-1 sigma layer
RH:0.72-0.94 sigma layer
RH:0.995 sigma level
RH:0C isotherm
RH:1 mb
RH:10 mb
RH:100 mb
RH:1000 mb
RH:150 mb
RH:2 m above ground
RH:2 mb
RH:20 mb
RH:200 mb
RH:250 mb
RH:3 mb
RH:30 mb
RH:30-0 mb above ground
RH:300 mb
RH:350 mb
RH:400 mb
RH:450 mb
RH:5 mb
RH:50 mb
RH:500 mb
RH:550 mb
RH:600 mb
RH:650 mb
RH:7 mb
RH:70 mb
RH:700 mb
RH:750 mb
RH:800 mb
RH:850 mb
RH:900 mb
RH:925 mb
RH:950 mb
RH:975 mb
RH:entire atmosphere (considered as a single layer)
RH:highest tropospheric freezing level
SNOD:surface
SOILW:0-0.1 m below ground
SOILW:0.1-0.4 m below ground
SOILW:0.4-1 m below ground
SOILW:1-2 m below ground
SPFH:2 m above ground
SPFH:30-0 mb above ground
SPFH:80 m above ground
SUNSD:surface
TMP:0.995 sigma level
TMP:1 mb
TMP:10 mb
TMP:100 m above ground
TMP:100 mb
TMP:1000 mb
TMP:150 mb
TMP:1829 m above mean sea level
TMP:2 m above ground
TMP:2 mb
TMP:20 mb
TMP:200 mb
TMP:250 mb
TMP:2743 m above mean sea level
TMP:3 mb
TMP:30 mb
TMP:30-0 mb above ground
TMP:300 mb
TMP:350 mb
TMP:3658 m above mean sea level
TMP:400 mb
TMP:450 mb
TMP:5 mb
TMP:50 mb
TMP:500 mb
TMP:550 mb
TMP:600 mb
TMP:650 mb
TMP:7 mb
TMP:70 mb
TMP:700 mb
TMP:750 mb
TMP:80 m above ground
TMP:800 mb
TMP:850 mb
TMP:900 mb
TMP:925 mb
TMP:950 mb
TMP:975 mb
TMP:PV=-2e-06 (Km^2/kg/s) surface
TMP:PV=2e-06 (Km^2/kg/s) surface
TMP:max wind
TMP:surface
TMP:tropopause
TOZNE:entire atmosphere (considered as a single layer)
TSOIL:0-0.1 m below ground
TSOIL:0.1-0.4 m below ground
TSOIL:0.4-1 m below ground
TSOIL:1-2 m below ground
UGRD:0.995 sigma level
UGRD:1 mb
UGRD:10 m above ground
UGRD:10 mb
UGRD:100 m above ground
UGRD:100 mb
UGRD:1000 mb
UGRD:150 mb
UGRD:1829 m above mean sea level
UGRD:2 mb
UGRD:20 mb
UGRD:200 mb
UGRD:250 mb
UGRD:2743 m above mean sea level
UGRD:3 mb
UGRD:30 mb
UGRD:30-0 mb above ground
UGRD:300 mb
UGRD:350 mb
UGRD:3658 m above mean sea level
UGRD:400 mb
UGRD:450 mb
UGRD:5 mb
UGRD:50 mb
UGRD:500 mb
UGRD:550 mb
UGRD:600 mb
UGRD:650 mb
UGRD:7 mb
UGRD:70 mb
UGRD:700 mb
UGRD:750 mb
UGRD:80 m above ground
UGRD:800 mb
UGRD:850 mb
UGRD:900 mb
UGRD:925 mb
UGRD:950 mb
UGRD:975 mb
UGRD:PV=-2e-06 (Km^2/kg/s) surface
UGRD:PV=2e-06 (Km^2/kg/s) surface
UGRD:max wind
UGRD:planetary boundary layer
UGRD:tropopause
USTM:6000-0 m above ground
VGRD:0.995 sigma level
VGRD:1 mb
VGRD:10 m above ground
VGRD:10 mb
VGRD:100 m above ground
VGRD:100 mb
VGRD:1000 mb
VGRD:150 mb
VGRD:1829 m above mean sea level
VGRD:2 mb
VGRD:20 mb
VGRD:200 mb
VGRD:250 mb
VGRD:2743 m above mean sea level
VGRD:3 mb
VGRD:30 mb
VGRD:30-0 mb above ground
VGRD:300 mb
VGRD:350 mb
VGRD:3658 m above mean sea level
VGRD:400 mb
VGRD:450 mb
VGRD:5 mb
VGRD:50 mb
VGRD:500 mb
VGRD:550 mb
VGRD:600 mb
VGRD:650 mb
VGRD:7 mb
VGRD:70 mb
VGRD:700 mb
VGRD:750 mb
VGRD:80 m above ground
VGRD:800 mb
VGRD:850 mb
VGRD:900 mb
VGRD:925 mb
VGRD:950 mb
VGRD:975 mb
VGRD:PV=-2e-06 (Km^2/kg/s) surface
VGRD:PV=2e-06 (Km^2/kg/s) surface
VGRD:max wind
VGRD:planetary boundary layer
VGRD:tropopause
VIS:surface
VRATE:planetary boundary layer
VSTM:6000-0 m above ground
VVEL:0.995 sigma level
VVEL:100 mb
VVEL:1000 mb
VVEL:150 mb
VVEL:200 mb
VVEL:250 mb
VVEL:300 mb
VVEL:350 mb
VVEL:400 mb
VVEL:450 mb
VVEL:500 mb
VVEL:550 mb
VVEL:600 mb
VVEL:650 mb
VVEL:700 mb
VVEL:750 mb
VVEL:800 mb
VVEL:850 mb
VVEL:900 mb
VVEL:925 mb
VVEL:950 mb
VVEL:975 mb
VWSH:PV=-2e-06 (Km^2/kg/s) surface
VWSH:PV=2e-06 (Km^2/kg/s) surface
VWSH:tropopause
WEASD:surface
WILT:surface
```



