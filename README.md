### GBC Inventory Preliminary Exploration - Summer/Fall 2021

#### Testing EuropePMC API and europePMC R package

* Script = STEP 1 

* Summary: Contains query for retrieving records and the code for getting the abstracts; some fussing to getting abstracts for records from other sources (def better way to do this) - API and package work great themselves.

#### Early coarse classification via title/abstract keywords

* Script = STEP 2

* Summary: Contains expected keywords that can be used as classifiers based on observations from manual curation (e.g. 'database' = positive, 'package' = negative). Titles tested via a crude cascade with a set of 638 manually curated records (variable hji_recheck) - looks promising. Scripts for abstract not complete. Note that classifiers for title vs. abstracts different (e.g. more and more granular for abstract). Title classifiers tested are directly in code and abstracts classifers are in a file. All preliminary.

* Note: file "manual_checks_hji_2021-08-20.csv" is the full set (638) manually curated records and file "manual_checks_hji_cec_2021-07-28.xlsx" is a subset of 20 that were especailly tricky - reviewed by both Chuck Cook (cec_manual_review) and Heidi Imker (hji_manual_review); see those columns for notes

#### Early URL processing

* Script = Step N

* Summary:  A challenge will be getting resource name - sometimes are contained within the URL. This was early cleaning/processing and testing of URL so see if they'll be useful - looks promising. Scripts partially work. Will be somewhere downstream in workflow, hence "Step N"

#### Misc - in Prelim folder

 * Also did testing against data from Wren et 2017 (doi:10.1093/nar/gkx182), some testing of stopwords, and use of re3data API for registered data resources (some may count for this inventory and some may not). 
