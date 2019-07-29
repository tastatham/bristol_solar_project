# Calculating Solar Irridiance for Individual Buildings in Bristol,England using LiDAR

A repository that shows how the Bristol Solar Team at the Open Data Bristol hackathon event (Nov 2018) estimated solar irridiance for buildings in Bristol, England using open data (LiDAR - Environment Agency) and open source tools (R,SAGA). 


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

To run the code, you will need to have R and SAGA installed. SAGA is a Geographic Information System (GIS) Free Open Source Software (FOSS). All required packages will be installed at the beginning of the rmarkdown.


#### Installing SAGA

To install SAGA on ubuntu;

```
sudo add-apt-repository ppa:johanvdw/saga-gis
sudo apt-get update
sudo apt-get install saga
```

For windows, we recommend downloading from OSGEO https://live.osgeo.org/en/download.html, which also contains several geospatial libaries (including GDAL/GRASS).

## Authors

* **Tom Statham** - *Calculating Solar Irridiance for Individual Buildings in Bristol,England using LiDAR* - [tastatham](https://github.com/tastatham)
* **Lenka Hasova** - *Part 2: Evaluating the potential for PV installations on building roofs* - [hasovalenka](https://github.com/hasovalenka)
* **David Saunders** - *For his domain knowledge of solar energy and project manager*  

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/tastatham/bristol_solar_project/LICENSE.md) file for details

## Credits
[Ordnance Survey for OS Zoomstack Buildings](https://www.ordnancesurvey.co.uk/business-and-government/licensing/using-creating-data-with-os-products/os-opendata.html).
[Environment Agency for LiDAR DSM 1m](https://www.ordnancesurvey.co.uk/business-and-government/licensing/using-creating-data-with-os-products/os-opendata.html).

## Acknowledgments

* We would like to thank Bristol City Council for the small stipend for carrying out this work.

