# About

TODO add some description.


Full dataset with additional [columns](https://docs.google.com/spreadsheets/d/1lvDKrp6Azkr8D-MTOOUsEX61wPxcG2LSZlep_gdK4U8/pubhtml?gid=1332420733&single=true) for years 1996 to 2013 can be downloaded [here](https://collegescorecard.ed.gov/downloads/CollegeScorecard_Raw_Data.zip).  Warning: This zip of csvs is ~ 150 MB.  Unzipped, each file is ~ 100 MB.


# Ways to get data

1. Ask for a USB at jam
1. Download from [here](https://collegescorecard.ed.gov/downloads/Most-Recent-Cohorts-Scorecard-Elements.csv)
1. Query the [API]()


# Definitions for columns (in Scorecard only data)

[See here](./definitions.md)

# Data Categories

Taken from [https://collegescorecard.ed.gov/data/documentation/](https://collegescorecard.ed.gov/data/documentation/).

## Root

These select items refer to the most basic information in the data set, including different IDs for each school.

* Unit ID and OPE ID for the institution
* Location (lat/long)

## School

A number of the elements produced in this data set provide basic descriptive information about the school in question. Most of these elements are already available through the Integrated Postsecondary Education Data System (IPEDS).

* Name
* Currently Operating status
* URLs for the Institution’s Homepage and Net Price Calculator
* Main vs Branch Campus
* Accrediting Agency
* Degree Type
* Public/Private Nonprofit/Private For-Profit
* Carnegie Classifications
* Specialized Mission or Religious Affiliation
* Distance-Education-Only Indicator
* School Revenue and Expenditures
* Heightened Cash Monitoring 2 Indicator

## Academics

These metrics describe the types of academics available at each institution.

* Percentage of Degrees Awarded by Program
* Programs Offered by Degree Type

## Admissions

These metrics describe the admission statistics for each institution.

* Acceptance Rate
* SAT and ACT scores

## Student

Several elements, including some that haven’t been published before, identify demographic and other details about the student body of the school. Some of the elements are available through the Integrated Postsecondary Education Data System, and others were produced using the National Student Loan Data System.

* Number of Undergraduate Students
* Undergraduate Student Body by Race/Ethnicity
* Undergraduate Students by Part-Time status
* Undergraduate Students by Age (25 or Over)
* Income Brackets of Federal Financial Aid Recipients
* Share of First-Generation Students
* Number of FAFSA Submissions to Colleges

Some data were produced as contextual information for the earnings cohorts in particular; the most recent data for these elements are for the 2005 and 2006 cohorts. These data include undergraduate students by: gender, age at entry, veteran status, and marital status.

## Cost

Information about the costs to students of a school can provide important context for students and families as they seek to evaluate the tradeoffs of access, affordability, and outcomes. While several of the elements in this category are commonly used elements from the Integrated Postsecondary Education Data System, others are new and/or different elements derived from the National Student Loan Data System.

* Average Cost of Attendance
* Tuition and Fees
* Average Net Price, by Income Level

## Aid

Financial aid can provide an important look at how much debt students take on to attend the college, the share of students who receive federal grants and loans to help pay for college, and how much the typical student can expect to owe each month after graduating.

* Percent of Undergraduates Receiving Federal Loans
* Percentage of Pell Grant Recipients
* Cumulative Median Debt, Disaggregated by Student Subgroups
* Typical Monthly Loan Payments of Graduates

## Repayment

To provide a sense for the debt burden of attending college and the loan performance metrics for each school, we produced several elements using the National Student Loan Data System. These elements can provide useful information for students and families concerned about borrowing for college and interested in seeing borrowers’ behavior after they leave the school.

* Cohort Default Rate
* Repayment Rate on Federal Student Loans, Disaggregated by Student Subgroups

## Completion

College completion is associated with other positive outcomes, like finding a job and successfully repaying student loans, and is an important metric for evaluating the experiences of students at the institution. However, both existing and new methods of measuring completion have limitations.

* Completion Rates for First-Time, Full-Time Students
* Retention Rates for First-Time Students
* 150 percent Completion Rate (IPEDS)
* 200 percent Completion Rate (IPEDS)
* Completion and Transfer Outcomes for Title IV Students, Disaggregated by Student Subgroups

## Earnings

One of the most common reasons students cite in choosing to go to college is the expansion of employment opportunities. To that end, data on the earnings and employment prospects of former students can provide key information. To measure the labor market outcomes of individuals attending institutions of higher education, data on cohorts of federally aided students were linked with earnings data from de-identified tax records and reported back at the aggregate, institutional level.

* Average and Median Earnings, Disaggregated by Student Subgroups
* Share of Former Students Earning Over $25,000
