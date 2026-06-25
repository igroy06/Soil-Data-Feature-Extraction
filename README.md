# Soil-Data-Feature-Extraction
This dataset provides a pan-European level in the spatial resolution of 20 m the degree of imperviousness change in the most relevant categories of sealing change (unchanged no sealing, new cover, loss of cover, unchanged sealed, increased sealing, decreased sealing) between the 2015 and 2018 Imperviousness Density status layers. This notebook will see the steps to access the data for **Hungary** (the country of interest) and see some samples and features of interest, using Python programming. 

## Understanding Imperviousness
In the *Copernicus High Resolution Layer Imperviousness* dataset: 
  1. High imperviousness values → More artificial/sealed surfaces (concrete, asphalt, buildings). These areas don’t absorb water well → more runoff,
     higher flood risk, less groundwater recharge.
  2. Low imperviousness values → More natural, permeable surfaces soil, vegetation). These areas can absorb and infiltrate water better → healthier         hydrology, less runoff, better for groundwater recharge.
     
“Low imperviousness” doesn’t always mean perfect soil. For example, clay-rich
soils might still have poor infiltration despite being “permeable” in land cover
terms.

Imperviousness is a land cover indicator, not a direct soil quality measure. It
mainly reflects human impact on the surface.

## Source of Raw Data
The raw data can be accessed from Copernicus Land Monitoring Service website.
[The Imperviousness Classified Change 2015-2018 (raster 20 m), Europe, 3-yearly](https://land.copernicus.eu/en/products/high-resolution-layer-imperviousness/imperviousness-classified-change-2015-2018) 
