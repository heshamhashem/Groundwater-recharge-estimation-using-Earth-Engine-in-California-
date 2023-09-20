# Groundwater-recharge-estimation-using-Earth-Engine-in-California-
## Groundwater recharge estimation using Earth Engine in California 

### We will go through 4 tasks to implement our project:

#### Task1:the Earth Engine python API will be initialized, some useful libraries will be installed & imported.

#### Task2:  OpenLandMap datasets related to soil properties will be explored. The wilting point and field capacity of the soil will be      calculated by applying some mathematical expressions to multiple images.


#### Task3:  evapotranspiration and precipitation datasets will be imported. A function will be defined to resample the time resolution of an ee.ImageCollection and to homogenize time index of both datasets. Both datasets will then be combined into one.

#### Task4: the Thornthwaite-Mather(TM) procedure will be implemented by iterating over the meteorological ee.ImageCollection. Finally, a comparison between groundwater recharge in two places ( Raisin City and Reefer City)  will be described and the resulting mean annual groundwater recharge will be displayed over California
