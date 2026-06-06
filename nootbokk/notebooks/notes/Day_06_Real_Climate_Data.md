# Day 06

Today I worked with a real climate dataset.

Key dimensions:
- time
- lat
- lon

I learned:

1. A map is data with dimensions (lat, lon)

2. A time series is data with dimension (time)

3. A single value has no remaining dimensions

4. mean(dim="time") creates a climatology map

5. mean(dim=["lat","lon"]) creates a regional time series

6. Climate datasets can be viewed as a stack of rasters through time.