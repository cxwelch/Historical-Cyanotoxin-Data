# Historical-Cyanotoxin-Data

This respository is a home for all exploratory data analysis using exports from the NW Toxin Algae database: https://www.nwtoxicalgae.org/Default.aspx

NW Toxic Algae is Washington's database for all cyanotoxin testing across the state, which is funded by the Department of Ecology, and guided by Department of Health's recreational guidance values for microcystin, anatoxin-a, saxitoxin, and cylindrospermopsin. All sampled sites in Washington can be viewed on the map embedded in the website and exported as CSV files. The website is also updated regularly with current advisories associated with exceedances, indicated by a red dot on the map. Green indicates a water body has been sampled and came back below threshold(s) and a black 'x' indicates all waterbodies that have been sampled in the past but do not have current advisories attached to them.

Below is a description of the different code files within this repository that are constantly being refined:

Cyano_data_2019-2024 --- Explores seasonal shifts in sampling history over the last six years based on toxin type, associated recreational guidance thresholds, and eventually how it compares against climate data (tbd).

Toxin-Sampling_History --- Explores sampling history by county since 2007. This is an attempt to visualize both where there may be capacity limitations at the county level (because opportunistic sampling is conducted at the discretion of the county health department) and how this has changed over time. It is also apparent that the higher resource counties (King, Pierce, Snohomish, Thurston, Kitsap) have a lot more capacity to sample and therefore have a stronger sampling history. It would be interesting to align this data with census tract data or county level median income data.
