# Analyzing-Causal-Language-in-Textual-Data-An-NLP-approach

This repository contains the code for a study analyzing textual data from abstracts of 3 empirical special education journal (Journal of Learning Disabilities, Excpetional Children, Learning Disabilities Quarterly). Specifically, the coded uploaded to this repository is for a natural language processing analysis using dependency parsing and a subsequent logisitic regression analysis to determine the predictive utility of linguistic element indicative of causal relationships.

The code for the NLP/Logistic regression analyses of SPED Abstract Data (abstracts_clean_data_Vfinal.csv)is found in abstract_data_analyses.ipbyn. These files can be downloaded by visiting the links above and clicking "download raw data".

Variables in the dataset explained:

* Observations (# of abstracts collected) = 235
* Journal ID = ID of empirical journal where the study was published (JLD = Journal of Learning Disabilities, EC = Excpetional Children, LDQ = Learning Disabilities Quarterly) 
* Volume # = Volume of the journal the study was published in 
* Issue # = Issue  of the journal the study was published in
* Year = Year published
* Title = title of the manuscript
* Author #1 = First author of the manuscript
* Design = (0 = Non-Experimental, 1 = Experimental)
* Text = abstract of the study (textual data to analyze)
* NW = Number of words per abstract
* CC = frequency of causal conjunctions per abstract
* SCONJ = frequency of subordinating conjunctions per abstract
* ADVCL = frequency of adverbial clauses per abstract
* DOBJ = frequency of direct objects per abstract
* IC = frequency of implicit causal verbs per abstract
