# CCRB-Complaints-Analysis

The project is based on complaints of NYPD misconduct data, collected by The Civilian Complaint Review Board (CCRB) https://www1.nyc.gov/assets/ccrb/downloads/excel/ccrb_datatransparencyinitiative_20170207.xlsx

Data is already cleaned and available in an excel sheet with the data dictionary. We will consider only incidents of years 2013-2016 and compare the 2016 forecast with its true value.

Since data are only up Feb '17, we will consider only incidents of years 2013-2016 and compare the 2016 forecast with its true value in order to evaluate prediction models performance. The best kind of predictor (with 2013-1015 training data) will be trained with 2013-2016 data and used to forecast "end of the year" 2017 results, using the 2016 data as Xpred.

Data from www1.nyc.gov/site/ccrb/policy/data-transparency-initiative-complaints.page
