# Project Overview 
The stability of a safe and clean water supply, both as a source of drinking water and as a marine environment,  is an important priority for the people of California and their elected officials. Understanding the larger picture of what harmful chemicals are in the water, both in the present moment and over time, is an important foundational step for public health officials in making effective  policy decisions and recommendations on these issues..

This analysis considers exactly this question, with regard to three main chemicals,: Mercury, Arsenic and Nitrate.

These are all substances with well established negative health consequences, which can be mitigated through a variety of directed action (regulation of substances or industries, changed practices, cleaning plants, etc.). Arsenic, for instance, has a variety of bad effects in drinking water at levels as low as 30 micrograms per milliliter (a.k.a "parts per billion" or ppb). According to the World Health Organization, exposure to high levels of arsenic in drinking water can lead to skin lesions, a variety of cancers, cardiovascular disease, and diabetes. For pregnant mothers, exposure to arsenic in water can also impact their children’s cognitive development and can lead to premature death.  Mercury, meanwhile, affects the human population mainly through the consumption of fish who have accumulated levels from a polluted environment, at levels even, lower, just 2ppb.

For our research, we used the current legal limits of all three chemicals to benchmark violations:

- Arsenic: 10 ppb
- Mercury: 2 ppb
- Nitrate: 10 mg/L

This group has submitted individual unique Jupyter notebooks for each group member:

- Angelica: [MercuryAnalysisAngelica.ipynb](https://github.com/AntoFa1990/CA_Water_Analysis/blob/main/Mercury%20Analysis%20Angelica.ipynb)
- Antonette:[Antonette-Ars-Final.ipynb](https://github.com/AntoFa1990/CA_Water_Analysis/blob/main/Antonette-Ars-Final.ipynb) & [Antonette-Merc-Final.ipynb](https://github.com/AntoFa1990/CA_Water_Analysis/blob/main/Antonette-Merc-Final.ipynb)
- Brittni:
- Lorela:
- Adam: [Arsenic-Water-Analysis-Adam.ipynb](https://github.com/AntoFa1990/CA_Water_Analysis/blob/main/Arsenic-Water-Analysis-Adam.ipynb)


# Research Questions
There are a number of ways to come at this question, and a number of datasets available with which to consider it. While we have a further discussion ahead of both the data we chose as a group, how we manipulated it, as well as individual findings, these were the five main questions we looked at and our individual areas of focus:

- What does the raw data of a single collection site over the entire historical period of collection look like?

- Is there a difference in the number of surface water samples vs. well water samples?

- Are the legal thresholds for Arsenic (10 ppb), Mercury (2 ppb), and Nitrates (10 mg/L) violated?

- What are the historic trends for the presence of Arsenic & Mercury among CA highested populated counties (LA, San Diego, Alameda, Sacramento)?

- Which counties have the highest levels of Mercury and is it correlated with population?

- What are the recent trends for Nitrate among CA most populated counties?

# Description of Dataset
Data was sourced from the publically available CA Open Data repositories, which houses a collection of numerous, state collected datasets about essential public infrastructure like water, housing,etc. Through Open Data, the California Department of Water Resources (DWR) offers a number of discrete “grab” water quality datasets, containing DWR-collected, current and historical, chemical and physical parameters found in drinking water, groundwater, and surface waters throughout the state. Specifically, this analysis considered the 4.5 mil. record "Lab Data" subset, which consisted of Lab samples taken from various wells in counties throughout California from 1952 (and sporadically before). Records included information on sample date, parameters tested for, type of sample and locational information.

Lab data downloaded from the CA Department of Water Resources:

- Arsenic: [Ar-Water-Lab-Data.csv](https://github.com/AntoFa1990/CA_Water_Analysis/blob/main/Ar-Water-Lab-Data.csv)
- Mercury: [Mer-Water-Lab-Data.csv](https://github.com/AntoFa1990/CA_Water_Analysis/blob/main/Mer-Water-Lab-Data.csv)
- Nitrate: [NO3_Water_Lab_Data.csv](https://github.com/AntoFa1990/CA_Water_Analysis/blob/main/NO3_Water_Lab_Data.csv) 

# Data Processing Pipeline + Software

# Findings

This water quality analysis revealed the complexities in dealing with environmental data.  The raw data show that long-term monitoring data quality depends on factors like sample collection methodology, time of sampling, availability of access to sites, and funding play a role in the quality and length of various data sets across sites.  Because of this, the CA water quality data needed to be transformed into common units of measurement, outliers needed to be identified, and sampling dates needed to be converted into the “datetime” format that Pandas can understand. Once cleaned, the following conclusions could be drawn from the data. 

- Plotting raw the time series of multiple stations with large data sets shows higher and more frequent peaks of Arsenic in water before the mid-1980’s. Factors that could have contributed to the decrease after 1990 include federal environmental regulation as well as higher fidelity of the instruments used in the sampling, among others.

- There is a prioritization of surface water sampling over ground water sampling.

- Arsenic and Mercury levels at the county level regularly surpass the legal threshold of 10 ppb and 2 ppb, respectively.

- There doesn’t appear to be a difference in Arsenic trends between Northern vs Southern Californian counties (LA & San Diego vs. Alameda and Sacramento).

- LA county exhibits the highest levels and frequency of Mercury spikes, most notably in the pre-1980s era.

- Nitrate levels frequently surpass the legal limit (10 mg/L) largely due to farm runoff in CA. 


# Challenges

# Next Steps
