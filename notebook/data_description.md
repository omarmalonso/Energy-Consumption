### Dataset description
This dataset contains data for energy consumption in the Chicago area for the year 2010. The electric data comes from ComEd and the gas data comes from Peoples Natural Gas; both collected by Accenture. Each row represents aggregated data for a specific combination of community area, census block, building type, and building subtype in.  
1.  Community and building Information
    - COMMUNITY AREA NAME: Community name.
    - CENSUS BLOCK: Census Block number obtained in the address matching/geocoding algorithms.
    - BUILDING TYPE: Whether buildings are residential, commercial, or industrial. Blank values indicate that the data for these Census Blocks is not available or applicable.
    - BUILDING SUBTYPE: Subtype of buildings( Single family, Multi-family < 7, multi-family 7+, commercial, industrial, municipal). Blank values indicate that the data for these Census Blocks is not available or applicable.

1.  Electricity consumption
    - KWH JANUARY 2010 TO KWH DECEMBER 2010: Kilowatt hours (kWh) for January 2010 - December 2010.
    - TOTAL KWH: Total consumption of electricity for 2010 (kWh).
    - ELECTRICITY ACCOUNTS: Number of distinct electricity accounts associated with the aggregated data in each row. Number of accounts does not equal number of buildings.
    - ZERO KWH ACCOUNTS: Number of accounts with 0 kWh amounts.

1.  Gas Consumption 
    - THERM JANUARY 2010 TO THERM DECEMBER 2010: Therm consumption for January 2010 - December 2010.
    - TOTAL THERMS: Total consumption of gas for 2010 (therms).
    - GAS ACCOUNTS: Number of distinct gas accounts associated with the aggregated data in each row. Number of accounts does not equal number  of buildings.

1. Descriptive statistics for electricity(kwh).
    Statistics based on consumption data within aggregated group.
    - KWH MEAN 2010
    - KWH STANDARD DEVIATION 2010
    - KWH MINIMUM 2010
    - KWH 1ST QUARTILE 2010
    - KWH 2ND QUARTILE 2010
    - KWH 3RD QUARTILE 2010
    - KWH MAXIMUM 2010
    - KWH SQFT MEAN 2010: Average kWh per square foot in 2010.
    - KWH SQFT STANDARD DEVIATION 2010
    - KWH SQFT MINIMUM 2010
    - KWH SQFT 1ST QUARTILE 2010
    - KWH SQFT 2ND QUARTILE 2010
    - KWH SQFT 3RD QUARTILE 2010
    - KWH SQFT MAXIMUM 2010

1. Descriptive statistics for gas(therms)
    Statistics based on consumption data within aggregated group.
    - THERM MEAN 2010
    - THERM STANDARD DEVIATION 2010
    - THERM MINIMUM 2010
    - THERM 1ST QUARTILE 2010
    - THERM 2ND QUARTILE 2010
    - THERM 3RD QUARTILE 2010
    - THERM MAXIMUM 2010
    - THERMS SQFT MEAN 2010
    - THERMS SQFT STANDARD DEVIATION 2010
    - THERMS SQFT MINIMUM 2010
    - THERMS SQFT 1ST QUARTILE 2010
    - THERMS SQFT 2ND QUARTILE 2010
    - THERMS SQFT 3RD QUARTILE 2010
    - THERMS SQFT MAXIMUM 2010

1. Square footage information
    - KWH TOTAL SQFT: Total square footage covered by electricity accounts. 
    - THERMS TOTAL SQFT: Total square footage covered by gas accounts.

1. Population and housing statistics
    Statistics based on consumption data within aggregated group.
    - TOTAL POPULATION: Total population.
    - TOTAL UNITS: Total units.
    - AVERAGE STORIES: Average number of stories.
    - AVERAGE BUILDING AGE: Average age for buildings.
    - AVERAGE HOUSESIZE: Average number of people living in each unit.
    - OCCUPIED UNITS: Number of occupied units.
    - OCCUPIED UNITS PERCENTAGE: Percentage of units that are occupied.
    - RENTER-OCCUPIED HOUSING UNITS: Number of units that are occupied by renters.
    - RENTER-OCCUPIED HOUSING PERCENTAGE: Percent of units that are occupied by renters.
    - OCCUPIED HOUSING UNITS: Numbers of housing units.