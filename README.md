# dati

## Open data archive for weather data measurements

![GitHub repo size](https://img.shields.io/github/repo-size/StazioneMeteoCocito/dati)
![GitHub last commit](https://img.shields.io/github/last-commit/StazioneMeteoCocito/dati)
![GitHub](https://img.shields.io/github/license/StazioneMeteoCocito/dati)


Open data for the [Cocito weather station](https://github.com/MatMasIt/weatherStation) project

The data is stored as csv with this format: `year/month/day/type.csv`

The data is available under the MIT License

|Data Type|Format|Unit of measurement |File type|
|---|---|---|---|
|Date|YYYY-MM-DD hh:mm:ss<hr />**Caution**: Time is expressed in ``CET`` (+1), italian local time|-|-|All|
|Temperature|decimal|°C|`temperature.csv`|
|Humidity|decimal|%|`humidity.csv`|
|Pressure|decimal|hPa|`pressure.csv`|
|Smoke|decimal|µg/m³|`smoke.csv`|
|PM10|decimal|µg/m³|`pm10.csv`|
|PM2.5|decimal|µg/m³|`pm25.csv`|
