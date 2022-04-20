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

<Stream discharge data was sourced from the USGS. Parameter code 00060 was used and resulted in a data frame with Discharge and Dates. The discharge data ranged from January 2000 through December 2021. Data was accessed on March 27, 2022.>

<Generation data was sourced from the EIA. Variables selected included the Month and "All fuels (ALL) megawatthours". Generation data ranged from January 2001 through December 2021. Data was accessed on March 27, 2022.>



## Folder structure, file formats, and naming conventions 

<The Raw Data folder contains csv files of hydroelectric generation data for each powerplant. The Processed folder primarily contains cleaned data for each gage and hydropower plant. The Processed folder also contains files containing the latitude and longitude of each stream gauge, as well as the locations and generation capacities of each power plant. All files are in csv format. Streamflow files were named after the identification number of each gauge, and generation files were named after the name of each hydropower plant. >

<Both file names and stored names for lists, plots, and tables indicates the hydropower plant or gage site along with the relvent test or function. For example gage_01563200_ts represented a time series for the gage site number 01563200.>


## Metadata

<For each data file in the repository, describe the data contained in each column. Include the column name, a description of the information, the class of data, and any units associated with the data. Create a list or table for each data file.> 
