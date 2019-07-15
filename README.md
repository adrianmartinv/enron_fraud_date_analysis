# enron_fraud_date_analysis
Analysis of the Enron fraud based only on the dates of the emails

## This is a fraud analysis from Enron emails dataset from https://www.cs.purdue.edu/commugrate/data/enron/

#### We have extracted all the dates from the email dataset into dates.txt with the next bash script
```bash
for file in `find ./maildir -type f` 

do
	echo -n "$file;"; sed -n 2p  $file 
	
done
```
