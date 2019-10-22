# ndvidata_r
Download and process NDVI data from www.ncei.noaa.gov

```{r}
url_path <- 'https://www.ncei.noaa.gov/data/avhrr-land-normalized-difference-vegetation-index/access/'
```

## Meta
 * netcdf files (.nc)
 * resolution 0.05 degrees (3-5 km)
 * daily time step
 * ndvi value is scaled with a factor = `0.0001` (e.g. 54356 = 0.54356)

## Notes

2018 is so far (2019-10-22) priliminary data.
