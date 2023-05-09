# independent_Project_Villarreal
My final independent project for Biol551, the data is based off of mitochondrial DNA in South American populations.


# Introduction
Native  indigonous population in the America continent orinated from individuals in East Asia roughly 18,000 years ago. when this migration accured, individuals with specific haplogroups had created populations throughout the the Americas. With the mtDNA data, we hope to identify variation in the mitochondrial DNA (mtDNA) in ancient Indigenous South American individuals and relate to the history of the first peoples in South America to see if there was any past gene flow, population structure, or population expansions.

# Data info
Data is focused on Haplogroups found in the South American samples to indicate what haplogroups were present in ancient samples from 9000-500 yearsold. The sample_ID labels the sample where region is found and what number that sample is within that region the haplogroups were orignially found within mitochondrial DNA (mtDNA) and identified through an online tool called haplogrep.
### Regions where samples were obtained
- CL: Colombia
- NC: Northern Coast
- SC: Southern Coast
- NH: Northern Highlands
- SH: Southern Highlands
- TR: Amazonian ancestry (buried in SH).



## Data Dictionary


| Column Name  | Data Type |                                         Description |
|:-------------------------:|:----------------:|--------------------------:|
|  Variable   |  Numeric  |   the name of sample |
|    Haplogroup(trim)    | Character | specific haplogroup of sample after trimming two base pairs |
|     Haplogroup(NOTtrim)      |  Character  |     specific haplogroup of sample before trimming two base pairs |
|     new     | Character |      filtered haplogroup after trimming to get broad haplogroup name|
|  region   | Character | locationwhere samples was obtained |


