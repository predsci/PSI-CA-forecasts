# PSI-CA-forecasts
A repository of the California infectious disease forecasts generated by Predictive Science.

### Directory Structure
The forecast submission files are divided into folders by disease. Within each disease is a 
folder for forecast visualization and a folder containing the submission CSV. 
### File Structure
The submission files are formatted according to the [FluSight](https://github.com/cdcepi/Flusight-forecast-data) specification, but with an extra 
column 'region_level' specifying the California region type ('region_flu' or 'region_healthofficer'). 
The region_level column is set to 'state' and location is set to 'CA' to indicate a forecast is for the 
entire state.  Otherwise, the location column is filled with a complete region name.

