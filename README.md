## Data Scientist job Opening in Fortune 500 Companies

#### Datasources:

 * Fortune 500 (csv file) from data.world
 * Job Openings from Indeed web scrapping

### Idea:
To find Data Scientist job openings in Fortune 500 companies across US. The data should be rich with the information such as number of employees, revenues, job location, salary range and job description.

Transformation:
*	Pulled Fortune 500 data in pandas data frame. Get company name, revenue, number of employees.
*	Scraped Indeed website for Data Scientist role across US for job title, company name, job location, salary, posting age.
*   Loaded all data in panda dataframes.
*   Cleaned Indeed data for complany name as it had extra words
*   Cleaned Indeed data for junk characters
*   Inner joined both data sets.

### Load:
*  Loaded the merged data into Postgres.

Challenges:
*  The company names did not exactly match because Indeed had extra words in the company name.
*  A pop up window was showing up unexpectedly when splinter clicked on the "next" button
*  Scraping Indeed turned out to be more complicated than we anticipated
*  Clicking the "next" button by splinter was not a link. We had to figure out a way to go to the next page
*  Indeed tags were not consistent.
