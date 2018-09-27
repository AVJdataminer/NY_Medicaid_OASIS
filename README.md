### NY_Medicaid_OASIS
## New York State Medicaid spending increased 325% from 2016 to 2017  
### Aiden V. Johnson  
### 09/26/2018  

[Read this on Medium](https://medium.com/@aiden.dataminer/new-york-state-medicaid-spending-increased-325-from-2016-to-2017-a4f3e4ea457)

The state of New York maintains a publicly available data set covering the most recent complete three years of medicaid claims data. This falls in line with the Open NY initiative started by Governor Cuomo to provide public access to the digital data associated with state government activities for empowering collaboration and analysis. The three year medicaid dataset is referred to as NYS OASAS Medicaid Trend Recipient Summary Profile and can be found on the Kaggle website and is updated annually. Let’s start with an overview of the dataset.

This data provides a detailed summary of recipients, units of service, paid claim dollars, dollars per individual and dollars per units of service for services reimbursed by Medicaid Fee for Service billing as well as Medicaid Managed Care Plans (beginning with SFY 2016–2017) for chemical dependence and non-chemical dependence services received for the current consecutive 3 state fiscal year window for which data is available and analyzed. Here is what we have for data columns:  

![data table](https://github.com/AVJdataminer/NY_Medicaid_OASIS/blob/master/IMGS/Screen%20Shot%202018-09-27%20at%203.26.43%20PM.png) 


The state of New York is in the top five for population in the US with about 19.8 Million people. According to the Kaiser Family Foundation on average 19% of the US population as of 2018 is covered by Medicaid/CHIP. Given these statistics we would expect there to be about 3.8 million Medicaid recipients in the state of New York; however, based on our analysis we found that in 2017 there were 4,099,152 unique recipients with Medicaid claims. This finding results in about 20.7% of the state’s population filling Medicaid claims a reasonable percentage based on population alone. Between year 2016 to 2017 the number of unique recipients rose 388%. In 2016 the number of recipients for the entire state was 1,619,971 this increased to 4,099,152 in 2017. This finding would lead one to anticipate a sizable an increase in Dollars spent between 2016 and 2017.

In addition to the number of recipients increasing tremendously in 2017 the number of Dollars spent in 2017 was 325% increase from the prior year. This is a precipitated by a 5% decrease in Dollars spent from 2015 to 2016. See the table below to easily compare the statewide changes across the last three years in Dollars spent, Claims received, and Recipients.

![year table](https://github.com/AVJdataminer/NY_Medicaid_OASIS/blob/master/IMGS/Screen%20Shot%202018-09-27%20at%202.59.07%20PM.png)


The third most compelling finding in this data set is the Dollars spent by Service nearly exclusively increases from 2016 to 2017. Not only are there far more unique recipients in 2017 than 2016, increasing. The statewide spending on Medicaid, there are also increased costs at service level. The only Service out of 21 labeled services provided to decrease in Dollars spent from 2016 to 2017 was DOH OP Psychiatric Services. See the figure below for a Service by service change in Dollars spent normalized by the number of recipients covered per year.  

![bar chart](https://github.com/AVJdataminer/NY_Medicaid_OASIS/blob/master/IMGS/Screen%20Shot%202018-09-27%20at%202.51.37%20PM.png) 

In summary, this analysis prompted many more questions around the drastic changes from 2016 to 2017. Especially in contrast to the similar metrics for Claims, Dollars, and Recipients from 2015 to 2016. Although the format of this data is maintained at a three-year interval having a fourth year would be helpful in this case. Additionally, some consideration has to be given to what would cause a across the board increase in Dollars by Service per Recipient increase.

Some interesting comparisons across Counties normalized by population level would be interesting as well. Perhaps there are “hotspots’ of chemical dependency type services or Counties that spend substantially more than others regardless of population size but due to some other socio-economic difference.



