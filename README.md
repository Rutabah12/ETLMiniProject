Data Scientist job Opening in Fortune 500 Companies

Datasources:

<1.> Fortune 500 (csv file) from data.world
<2.> Job Openings from Indeed web scrapping

Idea:
To find Data Scientist job openings in Fortune 500 companies across US. The data should be rich with the information such as number of employees, revenues, job location, salary range and job description.

Transformation:
•	Read Fortune 500 data in pandas data frame. Get company name, revenue, number of employees.
•	Scrape Indeed website for Data Scientist role across US for job title, company name, job location, salary, posting age.
•	Load the scraped data in pandas data frame.
•	Perform keyword cleansing of company name using both datasets.
•	Join the two datasets.

Load:
Load the data into Postgres.
