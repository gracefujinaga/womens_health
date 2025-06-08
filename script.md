# Get the IDs
esearch -db pubmed -query "menopause" | efetch -format uid > /Users/gracefujinaga/womens_health/data/menopause_ids.txt

esearch -db pubmed -query "erectile dysfunction" | efetch -format uid > /Users/gracefujinaga/womens_health/data/ed_ids.txt