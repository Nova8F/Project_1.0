# Chemicals in Cosmetics

## Team Members:

Rayshawn Moore, Ling Bramlett, Domenic Misiti, Marah Alsharaiha

## Project Summary:
In this project, the data collected from cosmetic companies in California was analyzed to draw conclusions about the frequency of potentially hazardous ingredients in cosmetic products. Questions explored included:
1. Which companies and brands have the most reports of potentially hazardous chemicals?
2. Which potentially hazardous chemicals have been reported the most?
3. Which product categories and subcategories contain the most reports of potentially hazardous chemicals?
4. What kind of changes were there in the reporting of potentially hazardous chemicals from year to year?

## Methods and Analysis (using Python in Jupyter Notebook)
1. Which companies and brands have the most reports of potentially hazardous chemicals?

Our analysis reveals that every company reported at least one chemical in their products, 
with the maximum number of chemicals utilized by a single company reaching nine. Notably, 
L'Oréal emerged as the leader in chemical usage, reporting an astonishing total of 5,711 chemicals. However, 
it is crucial to highlight that the predominant chemical in their products is Titanium Dioxide, 
which has been associated with serious health concerns, including DNA damage, skin irritation, 
and carcinogenic effects when inhaled.

Additionally, BareMinerals was identified as the top brand for chemical usage, 
particularly with 3,031 instances of Titanium Dioxide. Given its prevalence in our dataset, 
we aimed to investigate the other chemicals more thoroughly, excluding Titanium Dioxide. 
This deeper analysis led us to discover that Coty is the foremost company in chemical usage when Titanium Dioxide 
is not considered, with retinol being their primary chemical of concern. Retinol is known to have side effects such 
as skin irritation, increased sensitivity to sunlight, and potential teratogenic effects.

Furthermore, our focused analysis on companies producing baby products indicated that Harmon Stores had the highest chemical counts for lead and cadmium.
These heavy metals pose significant risks to child development, with cadmium in particular being linked to autism.

2. Which potentially hazardous chemicals have been reported the most?

Titanium dioxide was by far the most reported chemical, coming in at over 85% of the data. Titanium dioxide is considered a carcinogen when in powdered form, though it does not necessarily mean that all the products reported here are in powdered form. Retinal esters, silica, mica, and talc rounded out the top five most reported chemicals in the data set, with all of these chemicals having their own histories of causing body irritations and toxicity to health. 

When considering the chemicals reported in this data, it is also important to note that only companies that have generated sales of $1,000,000 or more were required to report. Additionally, companies must report regardless of the concentration level of that chemical in their product, so the data here does not indicate how much of a given chemical would be present in the product. Nonetheless, all the chemicals in this data set of been particularly signified as potentially hazardous chemicals. 

3. Which product categories and subcategories contain the most reports of potentially hazardous chemicals?
Analysis of the data showed there are 13 primary Categories and over 100 subcategories and 123 different hazardous chemicals. The Top 10 of each was looked at closely comparing both categories to the number of Hazardous chemicals. Out of the 13 primary Categories and subcategories the top ten containing the highest number of different hazardous chemicals are
Primary Category (1 being the highest)
1.	Skin care Products (20.4%)
2.	Hair Care Products (Non-coloring), (16.3%)
3.	Makeup products (non-permanent) (12.7%)
4.	Bath products (10.1%)
5.	Sun-Related Products (9.6%)
6.	Nail products (7.7%)
7.	Personal Care Products (7.7%)
8.	Fragrances (5.5%)
9.	Hair Coloring Products (5.5%)
10.	Shaving Products (4.3%)
The Top Ten subcategories are (1 being the highest)
1.	Skin Moisturizers (14.2%)
2.	Hair shampoos (11.7%)
3.	Facial cream (10.4%)
4.	Skin Cleaners (10.4%)
5.	Hair Styling (10.1%)
6.	Sunscreen (making a cosmetic claim), (9.6%)
7.	Hair Conditioners (Rinse-Out), (8.8%)
8.	Anti/wrinkling-Aging Products (making a cosmetic claim), (8.5%)
9.	Other skin care Products (8.3%)
10.	Body Washed (8.0%)

From the results of the Primary Category and The Subcategory Skincare products contain the highest number of different hazardous chemicals, where’s Shaving products has the least, but only compared to the top ten highest categories. If possible, in the future it would be better to compare data from other states. This would overcome a limited data set.


4. What kind of changes were there in the reporting of potentially hazardous chemicals from year to year?

The California Safe Cosmetics Program (CSCP) launched an online system for company reporting in 2009. The data represented in the analysis includes company reports between 2009 and 2020. There was a high influx of reported products in the first few years, as represented in our line graphs showing chemical reports by year. Year to year analysis also showed a few main findings: (1) Reports of potentially hazardous chemicals began to slowly increase again in the late 2010’s. (2) The primary chemical being reported year to year is titanium dioxide.

In looking at the most frequently reported company in this data, L’Oreal, it is apparent that the majority of their product reports came when reporting began and into the early 2010’s. Since then, their reports have leveled out near zero, which could indicate either minimal change in their product lineup and formulation, and/or a reduced usage of potentially hazardous chemicals. Additionally, the data shows that L’Oreal has almost exclusively been reporting titanium dioxide as the potentially hazardous chemical being used in their product. Interestingly, other companies seemed to continue reporting titanium dioxide usage into the late 2010’s, but L’Oreal was not a part of this trend.

Reports of product discontinuations by year and by chemical type were also analyzed in this project. Procter & Gamble reported the most discontinuations between 2009-2020, with over 2700 discontinuations in that time, which could indicate their increased attention to eliminate potentially hazardous chemicals in their products, or could indicate other sources of change internally or externally that led them to reformulate, remove, or readjust some of their products. L’Oreal fell outside of the top 10 companies to report discontinuations.

The most discontinued chemical, by percentage of discontinued reports out of initial reports, was mineral oils, checking in at a 31% rate of discontinuation. Mineral oils came in at tenth in the rankings of most reported chemicals. Meanwhile, titanium dioxide was by far the most reported chemical, yet its discontinuation rate ranked tenth, checking in at an 11% rate of discontinuation.

## Conclusion

Overall, the state of California made a large effort to begin tracking potentially hazardous chemical composition in the late 2000's, and our goal was to determine any noteable patterns and trends in what was being reported between 2009-2020. Here are the general findings from our analysis:
- L'Oreal was the most prominent reporter of potentially hazardous chemicals, due largely to their frequent usage of titanium dioxide in their products.
- Titanium dioxide reports began to increase again with each year in the late 2010's, but the increase was not due to L'Oreal usage of this chemical.
- Skin care products had the most reports of using potentially hazardous chemicals, with skin moisturizers standing out as the subcategory of products reporting the most chemicals.
- Procter and Gamble has reported the most discontinuations, while L'Oreal falls outside the top 10 companies discontinuing products.
- Mineral oils were the most discontinued chemical by percentage, while titanium dioxide ranked 10th in discontinuation rate.

In further analysis, it would be interested to explore:
- Any data reported on potentially hazardous chemicals in others states
- Any scientific findings about certain chemicals that might be influencing the inclusion of chemicals in cosmetic products
- The effect that this data reporting would have on consumers making decisions about certain products or companies
- Any continuation of these cosmetics trends into the early 2020's
