# NYISO  

# Data sources: 
### NYISO  
Links to the data files:  
[Main Site][1]  
[Forecasts][2]  
[Load Results][3]  
[Weather History][4]  

### NOAA  
  
NYC geographical information can be found [here][5].  
  
You can get a grid location by hitting `https://api.weather.gov/points/{latitude},{longitude}` [[example][6]].  
  
Once found, the forecast data can be pulled with `https://api.weather.gov/gridpoints/TOP/{gridX},{gridY}/forecast`[[example][7]].  
  
[Forecast API Information][8]  
Historic weather data can be downloaded from [here][10]. Choose the GHCN-Daily download option [[details][11]].  
  
### NCEI  
  
[NCEI API Information][9]  
  
###  

### Weather history
NOAA provides daily weather summaries, which have been visualized below:  
![Max Temp][max_temp]  
![Max Temp Zoomed][max_temp_zoomed]  
![Min Temp][min_temp]  
![Precipitation][precip]  

  
[1]: https://www.nyiso.com/power-grid-data  
[2]: http://mis.nyiso.com/public/P-7list.htm  
[3]: http://mis.nyiso.com/public/P-58Clist.htm  
[4]: http://mis.nyiso.com/public/P-7Alist.htm  
[5]: https://tools.wmflabs.org/geohack/geohack.php?pagename=New_York_City&params=40.661_N_73.944_W_region:US-NY_type:city(8175133)  
[6]: https://api.weather.gov/points/40.661,-73.944  
[7]: https://api.weather.gov/gridpoints/TOP/35,32/forecast  
[8]: https://www.weather.gov/documentation/services-web-api  
[9]: https://www.ncei.noaa.gov/support/access-data-service-api-user-documentation  
[10]: https://www.ncdc.noaa.gov/cdo-web/search
[11]: https://www.ncei.noaa.gov/metadata/geoportal/rest/metadata/item/gov.noaa.ncdc:C00861/html
[max_temp]: https://github.com/the-great-shazbot/nexml-nyiso/tree/master/data/charts/max_temp_plot.png
[max_temp_zoomed]: https://github.com/the-great-shazbot/nexml-nyiso/tree/master/data/charts/max_temp_zoomed_plot.png
[min_temp]: https://github.com/the-great-shazbot/nexml-nyiso/tree/master/data/charts/min_temp_plot.png
[precip]: https://github.com/the-great-shazbot/nexml-nyiso/tree/master/data/charts/precip_plot.png