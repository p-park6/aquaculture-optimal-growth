# Finding the Optimal Growth for Marine Aquaculture Species

This repository covers the optimal growth temperatures for Marine aquaculture species, focusing on West coast. About 21 percent of domestic fisheries come from these aquaculture farms, with the demand of seafood predicted to grow. [^1] The repository will show where on the west coast oceans were the best suited places are to raise these species.


## Highlights of this notebook:
-   combining vector/raster data in `.tif` form
-   resampling and masking raster data
-   map algebra
-   visualizing optimal growth on a map


## Note on reading in the data
Since the dataset is quite large to be pushed to Github, it is **highly recommended** to:

1. Download the data first
2. Upload it in the .rproj you are working in
3. Put the data file in the .gitignore file.

Data can be accessed [here](https://drive.google.com/file/d/1u-iwnPDbe6ZK7wSFVMI-PpCKaRQ3RVmg/view)

## What is included in this Repo?

```
.
├── LICENSE
├── R
│   ├── aquaculture-optimal-growth.html
│   ├── aquaculture-optimal-growth.qmd
│   └── aquaculture-optimal-growth_files
│       └── figure-html
│          ├── unnamed-chunk-6-1.png
│          ├── unnamed-chunk-6-2.png
│          ├── unnamed-chunk-7-1.png
│          └── unnamed-chunk-7-2.png
├── README.md
├── aquaculture-optimal-growth.Rproj
└── data
    ├── average_annual_sst_2008.tif
    ├── average_annual_sst_2009.tif
    ├── average_annual_sst_2010.tif
    ├── average_annual_sst_2011.tif
    ├── average_annual_sst_2012.tif
    ├── depth.tif
    ├── wc_regions_clean.dbf
    ├── wc_regions_clean.prj
    ├── wc_regions_clean.shp
    └── wc_regions_clean.shx
```



[^1]: NOAA Fisheries. Understanding Marine Aquaculture. https://www.fisheries.noaa.gov/insight/understanding-marine-aquaculture