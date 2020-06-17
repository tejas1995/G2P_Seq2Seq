DO NOT SHARE WITHOUT PERMISSION


==Pronunciation Data (pron_data)==
Files:
--gold_data_train
--gold_data_test
--all.phoible

These files contain word-pronunciation pairs from Wiktionary.
The test file contains at most 200 entries for 507 languages.
The train file contains remaining entries (exclusive of test)
for 311 languages, with a maximum of 10k entries.
The all file contains all entries scraped from Wiktionary 
(test + train + additional entries beyond the 10k limit).

The file format is:
iso_code \t script \t word \t cleaned pronuncation \t scraped pronunciation
e.g.,
aar	LATIN	lago	l a ɡ o	ˈlaɡo
