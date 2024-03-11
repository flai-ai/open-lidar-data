# Open Lidar Data

![cover.png](cover.png)

## Summary

Welcome to the __Open LiDAR Data__ repository, a centralized repository dedicated to consolidating LiDAR datasets from
across the world. Our mission is to address the fragmentation of LiDAR data, which is currently scattered across a
myriad of institutions, making it challenging for researchers, developers, and policy makers to access and utilize this
invaluable resource efficiently.

## About

LiDAR (Light Detection and Ranging) technology has become a critical tool in a variety of fields, including archaeology,
geography, forestry, and urban planning, among others. Recognizing the importance of LiDAR data, a growing number of
countries have initiated systematic national LiDAR scanning routines. However, the lack of a unified platform for
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

| Datasets                | Path                                     | License                                                              |
|-------------------------|------------------------------------------|----------------------------------------------------------------------|
| Belgium EODat 2013-2014 | `/data/BE/EODaS/LiDAR_DHMV_II-2013-2015` | [License](licenses%2FGratisopendatalicentieVlaanderenv12_bqxu2t.pdf) |
| TODO                    | TODO                                     | TODO                                                                 |
| Slovenia GURS 2024      | __COMING SOON__                          | TODO                                                                 |

For more easier overview you can explore datasets via [FlaiHub](hup.flai.ai) __(COMING SOON)__

In each path there are follwing folders with data:

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

_To find the name of file take a look at main path in __Overview__ and tiling schema, or go to [FlaiHub](hup.flai.ai) __(COMING SOON)___

#### Download Via URL

You can download files directly from URL.

Example:

    https://open-lidar-data.s3.eu-central-1.amazonaws.com/data/BE/EODaS/LiDAR_DHMV_II-2013-2015/copc/LiDAR_DHMV_2_P1_ATL12104_ES_52500_217000.copc.laz

_To find the name of file take a look at main path in __Overview__ and tiling schema, or go to [FlaiHub](hup.flai.ai) __(COMING SOON)___

## Tutorials

* [How to download data with FlaiHub](tutorials%2Fhow-to-download-data-with-flai-hub.md)

## Contributing

We welcome contributions from the community, whether it's adding new datasets, improving data accessibility, or
providing feedback on how we can better serve the needs of users. If you have LiDAR data you'd like to contribute or
suggestions for our project, please see our contribution guidelines or contact us directly.

## Change logs

