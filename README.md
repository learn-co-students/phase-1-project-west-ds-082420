South King County Opportunity Youth
===================
This project offers an updated estimate of the number of Opportunity Youth in South King County using the 2017 5-year American Community Survey


##Background
The SRP would like an update on the estimated number of OY in South King County. However, that estimation comes from a report that is over three years old. The task was to update the SRP on the current status of OY in South King County using updated data.

##Directory 

[Data Query](notebooks/exploratory/data_preparation.ipynb)

[`Report Notebook`](‘report.py’)


##A map visualizing South King County

![Map of South King County](Images/SouthKingCountyMap.png)

##Estimating the Population of South King County

Based on the [2016 report](https://roadmapproject.org/wp-content/uploads/2018/09/Opportunity-Youth-2016-Data-Brief-v2.pdf) an opportunity youth is defined by being Age 16-24 who is not enrolled in school or having a job. From the report it was also noted that seven King County, Washington school districts: Auburn, Federal Way, Highline, Kent, Renton, (South) Seattle, and Tukwila make up for 92 % of the County’s High poverty schools. The information above was used to create a data frame from the 2017 pums data. 
	
the [Sample Weighting](https://www2.census.gov/programs-surveys/acs/tech_docs/pums/ACS2013_2017_PUMS_README.pdf?#page=11)  was used to estimate the populations of each region.

A list of the opportunity youth by puma(region) was created from the data frame and the total population by summing the weights for each sample.


####Estimated OY Population results: 11530

The [2016 Road Map Project](https://roadmapproject.org/wp-content/uploads/2018/09/Opportunity-Youth-2016-Data-Brief-v2.pdf#page=4) shows the opportunity for youth to be around 18,000. This may be the result of using different sample weighting or regions. 
 
### Findings 

#### The 2017 Data

##### Regions:

Southeast Seattle and the Enumclaw region to the far southwest of the county have the lowest rates of OY youth in our study. The low OY population in SE seattle is not surprising as home values in Downtown and North Seattle neighborhoods skyrocket and employment opportunities grow in the city.  Seattle is the 3rd most gentrifying city in the U.S. <sup>6<sup> and many lower income people are moving south to find cheaper housing.  The Enumclaw region is very rural in nature, and borders Rainier National Forest.  However, it’s not clear how this affects employment and enrollment of youth.  The I-5 corridor hosts the greatest rates of OY in South King County.

As a result of this, we recommend focusing interventions in Burien, Renton, Federal Way, and Kent regions.

#### Changes from 2016 to 2017

Overall percentages of youth classified as OY fell between 2016 and 2017 among youth past high school age.  We believe this represents improving job prospects in King County due to a rapidly growing tech industry.  Even if new jobs are not in the industry itself, it attracts highly paid workers and the benefits trickle through the economy as a whole.  It also may be due to improved educational access for these age groups, but more research would be needed to confirm that.

By studying the rates of OY by educational attainment, we see more unemployed and unenrolled youth holding only a highschool diploma or GED in 2017 than 2016.  On the other hand, the rates of OY with some college or a college degree remained essentially the same or fell among all age groups.  We believe this represents greater opportunities for youth with college experience, and this is likely connected to the increase in higher skilled jobs spurred by the growing tech dependent economy.  A highschool diploma just doesn’t get one as far as it used to.

### Conclusions

The trend toward jobs requiring more education leads us to recommend improving access to community colleges and trade schools.  This should come in the form of tuition waivers, childcare subsidies, transportation allowances, living and food stipends, and targeted outreach.  With these interventions we can improve the lives of these youth and their contributions to our society and economy.

## Citations

<sup>1</sup> Yohalem, N., Cooley, S. 2016. “Opportunity Youth in the Road Map Project Region”. Community Center for Education Results. Available at: https://bit.ly/2P2XRF3.

<sup>2</sup> American Community Survey Office, 2019 “AMERICAN COMMUNITY SURVEY 2013-2017 ACS 5-YEAR PUMS FILES ReadMe”  Available at: https://bit.ly/35gFlRE.

<sup>3</sup> King County Groundwater Protection Agency, 2020, “South King County Groundwater Management Area” kingcounty.gov

<sup>4</sup> Balk, Gene.  2019, “New milestone in King County: Immigrant population tops 500,000”, The Seattle Times.

<sup>5</sup> “Who Are Opportunity Youth?” 2020, The Aspen Institute Forum for Community Solutions. The Aspen Institute Forum for Community Solutions

<sup>6</sup> Balk, Gene. 2019, “Seattle is the third most gentrifying U.S. city — but that might not be as bad as you think, study finds”, The Seattle Times.


## Citations

<sup>1</sup> Yohalem, N., Cooley, S. 2016. “Opportunity Youth in the Road Map Project Region”. Community Center for Education Results. Available at: https://bit.ly/2P2XRF3.

<sup>2</sup> Anderson, T., Braga, B., Derrick-Mills, T., Dodkowitz, A., Peters, E., Runes, C., and Winkler, M. 2019. “New Insights into the Back on Track Model’s Effects on Opportunity Youth Outcomes”. Urban Institute. Available at: https://bit.ly/2BuCLr1.

<sup>3</sup> Seattle Region Partnership. 2016. “King County Opportunity Youth Overview: Demographics of opportunity youth and systemic barriers to employment”. Available at: https://bit.ly/2oRGz37.

<sup>4</sup> Morton, N. 2019. “Nearly 19,000 youth in King County are neither working nor in school. How one Seattle nonprofit is changing that.” The Seattle Times. Available at: https://bit.ly/2W5EufR.
