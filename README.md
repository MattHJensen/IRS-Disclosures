# IRS-Disclosures
## Introduction
The IRS-Disclosures project contains counts from [DISCLOSURE REPORT FOR PUBLIC INSPECTION PURSUANT TO INTERNAL REVENUE CODE SECTION 6103(p)(3)(C)](https://www.jct.gov/search/?keyword=Disclosure%20report%20for%20public%20inspection%20pursuant%20to%20Internal%20Revenue%20code%20section%206103(p)(3)(C)&it=content) for calendar years 1995 to 2022. These reports are prepared by the Internal Revenue Service and published by the Joint Committee on Taxation. 

## Project Detail

`total.csv` contains the total count of disclosures. Here is how the IRS describes a disclosure, emphasis added: 

> The number of disclosures of tax information depends on the type of record disclosed and what constitutes a record subject to disclosure accounting. <strong>Generally, when the IRS discloses some part of one taxpayer’s record for one tax year or period, the IRS counts that as one disclosure.</strong> For example, if the IRS discloses a return transcript to a state tax agency, the IRS counts one disclosure for every tax year each time a transcript is disclosed. If the agency receives a transcript for two tax years, the IRS counts that as two disclosures. If the agency receives three different transcripts for the same taxpayer and tax year, the IRS counts three disclosures since each transcript is a separate record.


### Notes
- The row 'SUM' adds disclosures across all IRC Section 6103 subsection, as calculated by this project. The row 'TOTALS' is from the original IRC 6103 reports.

- Official corrections from the IRS have been incorporated `total.csv`, so the disclosure counts differ from the original reports in a few cases. Disclosure counts for Social Security Administration 6103(l)(20) & Bureau of Economic Analysis in the years 2012 & 2013 have been corrected; the disclosure counts of Child Support Enforcement Agencies 6103(l)(6) in the years 2013, 2014 & 2015 have been corrected. See pg 5 of JCX-89-15 and pg 6 of JCX-32-16 for the corrections. 

### Reference
The Joint Committee on Taxation & Internal Revenue Service (1996-2022). Disclosure Report For Public Inspection Pursuant To Internal Revenue Code Section 6103(p)(3)(C) 
