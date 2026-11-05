# Prioritizing potential aquaculture
EDS 223 HW3

## Repository purpose

Contains the script **aquaculture_analysis.qmd** used to develop a function for making maps that display the suitable aquaculture area within West Coast EEZs for different species. 

## Repository Structure

```{}
.
├── aquaculture_analysis.qmd
├── data
│   ├── average_annual_sst_2008.tif
│   ├── average_annual_sst_2009.tif
│   ├── average_annual_sst_2010.tif
│   ├── average_annual_sst_2011.tif
│   ├── average_annual_sst_2012.tif
│   ├── depth.tif
│   ├── wc_regions_clean.dbf
│   ├── wc_regions_clean.prj
│   ├── wc_regions_clean.shp
│   └── wc_regions_clean.shx
└── README.md
```

## Data access

**.gitignore** removes **data/** from this repository

To download the data yourself, click on this [Google Drive link](https://drive.google.com/file/d/1u-iwnPDbe6ZK7wSFVMI-PpCKaRQ3RVmg/view) 

Data files used in **aquaculture_analysis.qmd** analysis include:

1) `wc_regions_clean.shp`
2) `depth.tif`
3) `average_annual_sst_2008.tif`, `average_annual_sst_2009.tif`, `average_annual_sst_2010.tif`, `average_annual_sst_2011.tif`, `average_annual_sst_2012.tif`

## Author

Emalia Partlow

## References

The `wc_regions_clean.shp` data was sourced from **[Marineregions.org](https://www.marineregions.org/eez.php)**

The `depth.tif` data was sourced from **[General Bathymetric Chart of the Oceans (GEBCO)](https://www.gebco.net/data-products/gridded-bathymetry-data#area)**

The `average_annual_sst_YEAR.tif` data was sourced from **[NOAA’s 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1](https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php)**