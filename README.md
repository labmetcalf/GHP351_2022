# GHP351_2022

### Midterm exam questions

#### See the data file `site_S6_malaria_data.csv` above

You will need to access the data in this file to answer questions in section 3 of the Midterm exam

This is real data from on ongoing cohort study where individuals at this study site have been sampled at 3 time points beginning in August 2021

Click on the file `site_S6_malaria_data.csv` above, then click `Raw` to access the raw data file

You have multiple options for accessing the data:

1. Copy and paste into excel

- From your browser (after clicking `Raw`), select all the raw data, then paste into excel
- Navigate to the `Data` tab and click `Text to Columns`
- Select `Delimited` : `Comma` : `Finish`

2. Copy and paste into google sheets

- From your browser (after clicking `Raw`), select all the raw data, then paste into a google sheet
- Navigate to the `Data` tab and click `Split Text to Columns`

3. Download

- In Chrome (after clicking `Raw`), go to `File`, `Save Page As` and manually add the `.csv` extension to the file name
- Alternatively, in Chrome (after clicking `Raw`), right click to `Save As` and manually add the `.csv` extension to the file name
- In Safari (after clicking `Raw`), go to `File`, `Save As`, click `Save`, and `Append`

4. The downloaded file can be opened directly in excel or you can upload to google drive and open as a google sheet

5. For those familiar with R or another programming language, feel free to use

#### Data notes

The data table has the following columns:

1. `ind_code`: Contains a unique ID code for each individual enrolled in the cohort study
2. `dob_yr`: Contains the year of birth
3. `sex`: L = Lehilahy = Male (in Malagasy); V = Vehivavy = Female (in Malagasy)
4. `age_cat`: Age group
5. `T1_visit_date` `T2_visit_date` `T3_visit_date`: Date of clinical visit (for the 3 time points)
6. `T1_rdt_result` `T2_rdt_result` `T3_rdt_result`: Results of malaria rapid diagnostic test (RDT) (see below)

Malaria RDT results coding:

- `0` = negative
- `1` = positive
- `NA` = No data because individual was not sampled
