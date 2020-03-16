# NYC_children_BLL_EDA_Python
Exploratory Data Analysis in Python of children under 6 yrs of age with Elevated Blood Lead Levels (BLL) in NYC neighborhoods
Data was downloaded from NYC OpenData
https://data.cityofnewyork.us/Health/Children-Under-6-yrs-with-Elevated-Blood-Lead-Leve/tnry-kwh5

Here is a brief description of what I did with the data:
1. Created a Jupyter Notebook and read the csv file into a dataframe.
2. Removed the unnecessary columns from the dataframe and renamed some column names.
3. Checked a few data columns by using Pandas value_counts() function.
4. Using matplotlib and Seaborn library, generated side-by-side line plots of children with BLL>=5, BLL>=10, BLL>=15, for each NYC borough and all of NYC.
5. Since Brooklyn showed the most cases with high BLL in children, generated line plots for different ighborhoods in Brooklyn and found that Greenpoint neighborhood in Brookyn had the most cases of high BLL in children.
6. My findings matched well with the stories published in the media:
https://blogs.ei.columbia.edu/2017/10/09/many-backyards-in-brooklyn-neighborhood-are-contaminated-with-high-levels-of-lead/
