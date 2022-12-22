air_pollution.csv
period: 25-09-2021 to 30-12-2021
date - date in ymd_hms
PC4 - postcode
pm2.5 - particulate matter <2.5um in ug/m3
pm10 - particulate matter <10um in ug/m3
no2 - nitrogen dioxide in ug/m3
no - nitrogen oxide in ug/m3
so2 - sulphur dioxide in ug/m3

meteo.csv
period: 01-01-2021 to 31-12-2021
date - ymd_hms
PC4 - postcode
wd - wind direction in degrees 0-360
wd - wind speed in m/s
blh - boundary layer height in metres
tcc - total cloud cover in oktas (0-9)
ssrd - solar surface radiation downwards in W/m2 (see https://cds.climate.copernicus.eu/cdsapp#!/dataset/reanalysis-era5-single-levels?tab=overview for more information)

zichtop.csv
period: 01-01-2021 to 18-11-2021
pop_tot is total number of persons in PC4 for each time step
m00_30 is number of persons who have been there between 30 minutes and 1 hour
m30_60 number of persons between 30 mins and 60
and so on

GM0772_pop_mort.csv
period: 2021
PC4 - postcode
population - CBS population for postcode in 2021
frac - fraction of total population for that postcode
year - year
COPD - total mortality from Chronic Obstructive Pulmonary Disease. Obtained by multiplying the total mortality for Eindhoven (GM0772) by the population fraction for each postcode
IHD - total mortality from Ischemic Heart Disease. Obtained by multiplying the total mortality for Eindhoven (GM0772) by the population fraction for each postcode
LC - total mortality from Lung Cancer. Obtained by multiplying the total mortality for Eindhoven (GM0772) by the population fraction for each postcode
LRI - total mortality from Lower Respiratory Infections. Obtained by multiplying the total mortality for Eindhoven (GM0772) by the population fraction for each postcode
STROKE - total mortality from Stroke. Obtained by multiplying the total mortality for Eindhoven (GM0772) by the population fraction for each postcode

