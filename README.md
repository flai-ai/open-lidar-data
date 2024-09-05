# Open Lidar Data

![cover.png](cover.png)

## Summary

Welcome to the __Open LiDAR Data__ repository, a centralized repository dedicated to consolidating LiDAR datasets worldwide. Our mission is to address the fragmentation of LiDAR data, which is currently scattered across a
myriad of institutions, making it challenging for researchers, developers, and policymakers to access and utilize this
invaluable resource efficiently.

## About

LiDAR (Light Detection and Ranging) technology has become a critical tool in various fields, including archaeology,
geography, forestry, and urban planning. Recognizing the importance of LiDAR data, many
countries have initiated systematic national LiDAR scanning routines. However, the need for a unified platform for
accessing these datasets impedes the potential for innovation and research.

The Open LiDAR Data aims to fill this gap by:

* __Consolidating LiDAR Datasets__: Initially focusing on Europe and the USA, our repository will provide easy access to
  a comprehensive collection of national LiDAR datasets.
* __Facilitating Research and Development__: By offering an organized and centralized data hub, we enable researchers
  and developers to harness LiDAR data for various applications, fostering innovation and knowledge creation.
* __Planning for Global Expansion__: While our initial efforts concentrate on Europe and the USA, we envision expanding
  our repository to include LiDAR datasets from other countries and continents, striving for global coverage.

## Data

### Overview

| Datasets                                       | Path                                                     | License                                                                                                                           | Source                                                                                                                                                     |
|------------------------------------------------|----------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------
| Belgium EODat 2013-2015                        | `/data/BE/EODaS/LiDAR_DHMV_II-2013-2015`                 | [License](licenses%2FGratisopendatalicentieVlaanderenv12_bqxu2t.pdf)                                                              | [EODaS openlidar](https://remotesensing.vlaanderen.be/apps/openlidar/#collapseDataDownload)                                                                |
| Belgium SPW 2021-2022                          | `/data/BE/SPW/Lidar_2021-2022`                           | The user can download any required data, without any limitations.                                                                 | [The Waloon geographical information website](https://geoportail.wallonie.be/catalogue/ab14b035-c9b0-4c79-a2b6-36811fca96a1.html)                          |
| Denmark SDFI 2018-2022                         | `/data/DK/SDFI/DHM_2018-2022`                            | [License](https://dataforsyningen.dk/asset/PDF/rettigheder_vilkaar/Vilk%C3%A5r%20for%20brug%20af%20frie%20geografiske%20data.pdf) | [The Board for Data Supply and Infrastructure](https://dataforsyningen.dk/data/3931#description)                                                           |
| Estonia Maa-amet 2011-2023                     | `/data/EE/Maa-amet/ALS_2011-2023`                        | [License](https://geoportaal.maaamet.ee/docs/Avaandmed/Licence-of-open-data-of-Estonian-Land-Board.pdf)   <br/>  Please refer to the Land Board and date when using the data. For example: "Elevation data, Land Board 2017-2020"                 | [Estonian Land Board](https://geoportaal.maaamet.ee/eng/Spatial-Data/Elevation-Data-p308.html)                                                             |
| Finland NLS 2008-2023                          | `/data/FI/NLS/05p_year_*`                                | [License](https://creativecommons.org/licenses/by/4.0/)                                                                           | [National land survey of Finland - MapSite](https://asiointi.maanmittauslaitos.fi/karttapaikka/)                                                           |
| Latvia LGIA 2013-2019                          | `/data/LV/LGIA/Lidar_2013-2019`                          | [License](https://www.lgia.gov.lv/sites/lgia/files/document/Atverto%20datu%20licence%20CC%20BY_0.pdf)                             | [Latvian Geospatial Information Agency](https://www.lgia.gov.lv/lv/Digit%C4%81lais%20virsmas%20modelis)                                                    |
| Netherlands AHN 2020-2022                      | `/data/NL/AHN/AHN4_2020-2022`                            | The AHN datasets are available as Open Data. This means that the data can be used by everyone for free and without restrictions.  | [Actueel Hoogtebestand Nederland](https://ahn.arcgisonline.nl/ahnviewer/)                                                                                  |
| Poland GUGiK 2018-2023                         | `/data/PL/GUGiK/Skaning_laserowy_*`                      | The user can download any required data, without any limitations.                                                                 | [geoportal.gov.pl](https://mapy.geoportal.gov.pl/imap/Imgp_2.html)                                                                                         |
| Slovenia ARSO 2011-2015                        | `/data/SI/GURS/LLS_2011-2015`                            | [License](http://www.evode.gov.si/fileadmin/user_upload/Lidar_pogoji_uporabe.pdf)                                                 | [Agencije RS za okolje - Atlas okolja](https://gis.arso.gov.si/evode/profile.aspx?id=atlas_voda_Lidar%40Arso&initialExtent=402591.76%2C39904.09%2C2.64583) |
| Switzerland SFA 2022                           | `/data/CH/Swiss_federal_authorities/swisssurface3d_2022` | [License](https://www.swisstopo.admin.ch/en/terms-of-use-free-geodata-and-geoservices)                                            | [Swiss federal authorities - Federal Office of Topography swisstopo](https://www.swisstopo.admin.ch/en/height-model-swisssurface3d)                        |
| Germany GeoSN 2015-2023                        | `/data/DE/GeoSN/lidar_2015-2023`                         | [License](https://www.govdata.de/dl-de/by-2-0)                                                                                    | [GeoSN - open data](https://www.geodaten.sachsen.de/batch-download-4719.html)                                                                              |
| United Kingdom DEFRA 2005-2022                 | `/data/DEFRA/LIDAR_*`                                    | [License](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)                                             | [DEFRA - Data Services Platform](https://environment.data.gov.uk/dataset/094d4ec8-4c21-4aa6-817f-b7e45843c5e0)                                             |
| Luxembourg le gouvernement luxembourgeois 2019 | `/data/LU/Gouvernement_LUX/Lidar_2019`                   | [License](https://creativecommons.org/publicdomain/zero/1.0/)                                                                     | [The luxembourgish open data platform - data.public.lu](https://data.public.lu/en/datasets/lidar-2019-releve-3d-du-territoire-luxembourgeois/)             

For a more accessible overview, you can explore datasets via [FlaiHub](https://hup.flai.ai) 

In each path, there are the following folders with data:

* `.../copc`
* `.../laz`


### Data Formats

All datasets are stored in original data format (LAS or LAZ) and in [COPC](https://copc.io/).  

### Access

#### Download via the Flai Hub

Download the link to the file.

#### Download Via S3

You can download files with [AWS CLI](https://aws.amazon.com/cli/).

Example:

    aws s3 cp s3://open-lidar-data/data/BE/EODaS/LiDAR_DHMV_II-2013-2015/copc/LiDAR_DHMV_2_P1_ATL12104_ES_52500_217000.copc.laz

_To find the name of the file take a look at the main path in __Overview__ and tiling schema, or go to [FlaiHub](hup.flai.ai).

#### Download Via URL

You can download files directly from the URL.

Example:

    https://open-lidar-data.s3.eu-central-1.amazonaws.com/data/BE/EODaS/LiDAR_DHMV_II-2013-2015/copc/LiDAR_DHMV_2_P1_ATL12104_ES_52500_217000.copc.laz

_To find the name of the file take a look at the main path in __Overview__ and tiling schema, or go to [FlaiHub](hup.flai.ai).

## Tutorials

* [How to download data with FlaiHub](tutorials%2Fhow-to-download-data-with-flai-hub.md)

## Contributing

We welcome contributions from the community, whether it's adding new datasets, improving data accessibility, or
providing feedback on how we can better serve users' needs. If you have LiDAR data you'd like to contribute or
suggestions for our project, please see our contribution guidelines or contact us directly.

## Change logs

