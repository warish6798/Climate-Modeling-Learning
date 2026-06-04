# Day 02 - Understanding Xarray DataArray

Today we learn how to create and work with an Xarray DataArray. A DataArray stores data along with its dimensions and coordinates, making it easier to handle climate and geospatial datasets.

I created a simple temperature dataset with time, latitude, and longitude dimensions. we will learn the difference between data values, dimensions, and coordinates, and how they work together to describe climate information.

I used `isel()` to select data by position and extracted individual values, maps, and time slices. I also plotted a temperature grid and calculated the mean temperature across the time dimension using `mean(dim="time")`.

This helped me understand how climate datasets are structured and how Xarray can be used to analyze NetCDF and CMIP climate model data.
