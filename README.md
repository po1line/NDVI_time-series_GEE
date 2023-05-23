# NDVI_time-series_GEE
🗾 Daily MODIS data processing across large territories using GEE API

Regional MODIS time series could be helpful support for large-scale vegetation monitoring and mapping. 
In this analysis, pilot regions in the Northern Hemisphere representing mostly boreal landscapes were used. The main task was to collect and analyse daily NDVI data to select relevant periods within each season -- summer, spring, autumn and winter for the next steps of satellite images processing in tasks based on time series.
The following rules can be suggested:
1) Summer season can be represented by week  with maximum NDVI values +- 2 weeks;
2) Autumn and spring period of decrease and increase of vegetation productivity  processes can be represented by NDVI values between 0.2 and 0.5 within corresponding seasons
3) For winter, working with periods from the middle of January to the end of February (for selected pilot regions) is generally ok. 
 
The code is presented in Jupyter Notebook. It works using GEE Python API, which requires authentication. The detailed guideline can be found [here](https://developers.google.com/earth-engine/tutorials/community/intro-to-python-api).


