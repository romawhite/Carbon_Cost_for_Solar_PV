# Unveiling Vegetation Carbon Losses from Global Utility-Scale Solar Photovoltaic Expansion

This is only for visualizing the key dataset and results in the paper '***Unveiling Vegetation Carbon Losses from Global Utility-Scale Solar Photovoltaic Expansion***'.
You can also access the codes for data analysis and visualization at https://github.com/romawhite/SolarPV and the codes for future solar pv sitting at https://github.com/romawhite/solarpv_siting.
Permission may be required to access the codes, but be granted upon request.
Any question please contact Dr. Wan via the email: roma@link.cuhk.edu.hk


## Step 1: Entrance
Go to the website: https://romawhite90325.users.earthengine.app/view/solarpv

## Step 2: Data selection
Choose image to be display, default image is yearly NIRv.

## Step 3: Solar PV location
Select ground-mounted utility-scale solar pv (PV<sub>GU</sub>) station to view details.

All PV<sub>GU</sub> are filtered based on the identifier of "group id".

There is two ways to select PV<sub>GU</sub>. You can select the targeted PV<sub>GU</sub> based on its properties. 
For example, if you want to view the largest PV<sub>GU</sub> in China, you can choose
```
Land cover: "All types"
Nation: "China"
sorted by: "area"
Group id: the first one is what you want if you select the sorting order as descending.
```
Or, you can view the map and click the polygon of targeted PV<sub>GU</sub>.

## Step 4: Details
View the details on the carbon cost
You can view the basic info, such as land cover, area, nation, etc., and differences in NIRv between solar land and buffer zones.
Also you can view the NPP loss, biomass loss and other info related to carbon.

## Step 5: Pixel inspector
You can also view the basic info at any pixel, including monthly NIRv.
