# snackrequests

This parser ingests snack requests from Enigma employees via our FTP under _/enigma.unpublished/snackrequests_unpublishedcollection2.csv_. 

## Parsing Strategy

Excel file was converted to CSV and stored to our FTP. The email column was deleted from the file to preserve anonymity. Dates were parsed using standard library step. Nulls were coerced to none. This is a one off parse. 

## Datasource Notes

Data is from Stephanie's online google excel sheet for snack requests. 

## Contacts

* [India Kerle](india.kerle@enigma.com)
