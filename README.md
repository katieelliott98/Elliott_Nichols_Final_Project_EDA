# <Elliott_Nichols_Final_Project_EDA>

## Summary

<In this project we set out to explore the relationship between hydropower generation and stream discharge.Hydroelectric power accounts for 52 percent of renewable electricity generation and 7 percent of total electricity generation in the US. These plants are a critical clean energy resource for grid operators and utilities due to their operational flexibility, low maintenance costs, and non-intermittent production. However, hydroelectric generation is susceptible to climate change, and changes in temperature, precipitation patterns, glacial melt, and the frequency of extreme weather events such as floods and droughts may have a direct negative effect on electricity production. Thus, the impact of climate change on the variability and availability of streamflow is critical for current hydroelectric generation and future operational forecast plans.>

<For our analysis, we looked at power generation data from the EIA and stream gage data from the USGS. For generation data we selected generation sites/dams so that half were from the western United States and half from the East. Stream gage data was selected upstream from dams and reservoirs to get an accurate representation of stream flow over time. Both power generation data and stream flow were analyzed for seasonality and monotonic trends using a seasonal mann kendall test. This was to help understand if generation was increasing or decreasing as a result of stream flow. Outside factors not included in the analysis could also contribute to increases or decreases in power generation.>

## Investigators

<Kaitlyn Elliott, Duke MEM, kaitlyn.e.elliott@duke.edu>

<Jon Nichols, UNC MBA, Jonathan_Nichols@kenan-flagler.unc.edu>


## Keywords

<Hydropower>
<Electricity>
<Streamflow>
<Climate Change>
<Discharge>
<Hydroelectric>
<Water>

## Database Information

<Stream discharge data was sourced from the USGS. Parameter code 00060 was used and resulted in a data frame with Discharge and Dates. The discharge data ranged from January 2000 through December 2021. Discharge is reported in ft^3/s. Data was accessed on March 27, 2022.>

<Generation data was sourced from the EIA. Variables selected included the Month and "All fuels (ALL) megawatthours". Generation data ranged from January 2001 through December 2021. Power is reported in units of megawhatthours. Data was accessed on March 27, 2022.>



## Folder structure, file formats, and naming conventions 

<The Raw Data folder contains csv files of hydroelectric generation data for each powerplant. The Processed folder primarily contains cleaned data for each gage and hydropower plant. The Processed folder also contains files containing the latitude and longitude of each stream gauge, as well as the locations and generation capacities of each power plant. All files are in csv format. Streamflow files were named after the identification number of each gauge, and generation files were named after the name of each hydropower plant. >

<Both file names and stored names for lists, plots, and tables indicates the hydropower plant or gage site along with the relvent test or function. For example gage_01563200_ts represented a time series for the gage site number 01563200.>

## Metadata

<Complete generation datasets in the processed folder contain the following information:

Date - Date the data was recorded. EIA data was given in months. An arbitrary day was added to overcome execution errors in R. 
Month - Month the data was recorded
Year - Year the data was recorded 
Power - the amount of power generated by the hydropower plant for that particular month. Units are megawatt hours (MWh)

Streamflow datasets in the processed folder contain the following information:

Year - Year the data was recorded 
Month - Month the data was recorded
Average Monthly Discharge - the average monthly streamflow for each gauge. Units are in cubic feet per second
Day - arbitrary day added to the month to avoid execution errors in R
Date - Date the data was recorded > 



