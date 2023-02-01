# Project Overview 
The stability of a safe and clean water supply, both as a source of drinking water and as a marine environment,  is an important priority for the people of California and their elected officials. Understanding the larger picture of what harmful chemicals are in the water, both in the present moment and over time, is an important foundational step for public health officials in making effective  policy decisions and recommendations on these issues..

This analysis considers exactly this question, with regard to three main chemicals,: Mercury, Arsenic and Nitrate.

These are all substances with well established negative health consequences, which can be mitigated through a variety of directed action (regulation of substances or industries, changed practices, cleaning plants, etc.). Arsenic, for instance, has a variety of bad effects in drinking water at levels as low as 30ppb. According to the World Health Organization, exposure to high levels of arsenic in drinking water can lead to skin lesions, a variety of cancers, cardiovascular disease, and diabetes. For pregnant mothers, exposure to arsenic in water can also impact their children’s cognitive development and can lead to premature death..  

Mercury, meanwhile, affects the human population mainly through the consumption of fish who have accumulated levels from a polluted environment, at levels even, lower, just 2ppb.


# Research Questions
There are a number of ways to come at this question, and a number of datasets available with which to consider it. While we have a further discussion ahead of both the data we chose as a group, how we manipulated it, as well as individual findings, these were the five main questions we looked at and our individual areas of focus:
What is the data picture of a single collection site over the entire historical period of collection? (Adam)
What are the difference in surface water samples vs. well water samples? (Antonette)
What are the historic trends for the presence of Arsenic & Mercury  among CA highested populated counties (LA, San Diego, Alameda, Sacramento)? (Lorela)
What are the recent  trends for Nitrate among CA most populated counties? (Brittni)
What are the recent  trends for Mercury among CA most populated counties? (Angelica)


# Description of Dataset
Data was sourced from the publically available CA Open Data repositories, which houses a collection of numerous, state collected datasets about essential public infrastructure like water, housing,etc. Through Open Data, he California Department of Water Resources (DWR) offers a number of discrete “grab” water quality datasets, containing DWR-collected, current and historical, chemical and physical parameters found in drinking water, groundwater, and surface waters throughout the state. Specifically, this analysis considered the 4.5 mil. record "Lab Data" subset, which consisted of Lab samples taken from various wells in counties throughout California from 1952 (and sporadically before). Records included information on sample date, parameters tested for, type of sample and locational information.

# Data Processing Pipeline + Software

# Findings

This water quality analysis revealed the complexities in dealing with environmental data.  The raw data show that long-term monitoring data quality depends on factors like sample collection methodology, time of sampling, availability of access to sites, and funding play a role in the quality and length of various data sets across sites.  Because of this, the CA water quality data needed to be transformed into common units of measurement, outliers needed to be identified, and sampling dates needed to be converted into the “datetime” format that Pandas can understand. Once cleaned, the following conclusions could be drawn from the data. 

- Plotting raw station data show higher and more frequent peaks of Arsenic in water before the mid-1980’s. Factors that could have contributed to the decrease after 1990 include federal environmental regulation as well as higher fidelity instruments used in the sampling, and among others.

- Arsenic and Mercury levels regularly violate the legal threshold (10 ppb and 2 ppb, respectively).

- There is a prioritization of surface water sampling over ground water sampling.

- There doesn’t appear to be a difference in Arsenic trends based on Northern vs Southern Californian counties (LA & San Diego vs. Alameda and Sacramento).

- LA county exhibits the highest levels and frequency of Mercury spikes, most notably in the pre-1980s era.

- Nitrate levels frequently surpass the legal limit (10 mg/L) largely due to farm runoff in CA. 


# Challenges

# Next Steps
