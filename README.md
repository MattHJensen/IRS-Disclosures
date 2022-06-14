# IRS-Disclosures
## Introduction
The IRS-Disclosures project contains counts from [DISCLOSURE REPORT FOR PUBLIC INSPECTION PURSUANT TO INTERNAL REVENUE CODE SECTION 6103(p)(3)(C)](https://www.jct.gov/search/?keyword=Disclosure%20report%20for%20public%20inspection%20pursuant%20to%20Internal%20Revenue%20code%20section%206103(p)(3)(C)&it=content) for calendar years 1995 to 2021. These reports are prepared by the Internal Revenue Service and published by the Joint Committee on Taxation. 

## Project Detail
Three files are included in this repo:
- `master.csv` is the count of disclosures generated from Bulk Master File

> Bulk Master File Data: Disclosures are generated when an agency receives data from an IRS database extract of taxpayer information. Each extract contains different data elements of a taxpayer’s account information based on the nature and purpose of the specific extract. A block of data elements for one taxpayer for one year or period constitutes one record and is counted as one disclosure. In order to account for any disclosure, the taxpayer’s identity information (taxpayer’s name, identification number and/or address) is included in every extract record. Other data specific to that extract is included in the record depending on the extract. Each record, regardless of amount of data elements constitutes one disclosure. Examples of varying data elements within a record include, for example: income; specific line items (or unique combinations of line items) from a tax return; account transactions (payments, assessments, refunds, adjustments); math and audit adjustments; filing dates and other filing activities such as extensions, filing status and exemptions. Each tax year or period disclosed for each record is counted as one disclosure.

- `other.csv` is the count of disclosures generated not from Bulk Master File 

> Disclosures that are not bulk/extract disclosures also vary depending on what is included in the record. Disclosures are made when the IRS releases transcripts of accounts, permits inspection of or furnishes photocopies of records, makes oral disclosures, and any disclosure by means of correspondence without furnishing a copy of the record. Also included are disclosures from locally automated files. Examples include copies of examination or collection administrative files. When some or all of the contents of an administrative file are disclosed, the IRS counts the number of disclosures based on the number

- `total.csv` is the total count of disclosures 

> The number of disclosures of tax information depends on the type of record disclosed and what constitutes a record subject to disclosure accounting. Generally, when the IRS discloses some part of one taxpayer’s record for one tax year or period, the IRS counts that as one disclosure. For example, if the IRS discloses a return transcript to a state tax agency, the IRS counts one disclosure for every tax year each time a transcript is disclosed. If the agency receives a transcript for two tax years, the IRS counts that as two disclosures. If the agency receives three different transcripts for the same taxpayer and tax year, the IRS counts three disclosures since each transcript is a separate record.


### Notes
- In all three forms, the row 'SUM' adds disclosures across all IRC Section 6103 subsection, as calculated by this project. The row 'TOTALS' is from the original IRC 6103 reports. The reason for mismatches between 'SUM' and 'TOTAL' is still unclear. 

- Corrections reported in later years have been updated in prior years here, so the disclosure numbers may in some cases differ from the original reports. Disclosure counts for Social Security Administration 6103(l)(20) & Bureau of Economic Analysis in the years 2012 & 2013 have been corrected; the disclosure counts of Child Support Enforcement Agencies 6103(l)(6) in the years 2013, 2014 & 2015 have been corrected. See pg 5 of JCX-89-15 and pg 6 of JCX-32-16 for the corrections. 

### Reference
The Joint Committee on Taxation & Internal Revenue Service (1996-2021). Disclosure Report For Public Inspection Pursuant To Internal Revenue Code Section 6103(p)(3)(C) 
