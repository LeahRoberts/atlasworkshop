---
layout: post
title: "Optional Scenarios: Now For Something Different"
categories: Miscellaneous
---

# Scenarios

**This section is optional and is an example of more thorough analyses you could explore with Atlas.**

Now that you are familiar with the platform, we are going to look at some real world examples of how you might use Atlas. Below we have three different scenarios for you to choose from. We have outlined how you might begin to look at the data, but you are free to explore and adapt as you see fit. 

**NOTE:** in a future release of Atlas users will be able to download spreadsheets containing relevant metadata from a selection of samples. Currently, however, this feature has not been implemented. To assist you with this workshop, we have pre-downloaded a number of spreadsheets to assist you with your analysis. 

## Scenario 1: Exploring South African Tuberculosis

South Africa has a high burden of Tuberculosis, which is reflected in the huge number of samples from South Africa in Atlas. For this scenario, you will be able to explore different facets of this data, including transmission and resistance dynamics. 


### Step 1:

In Atlas, filter for samples from South Africa. From here, you might want to also explore: 

1. Date range of samples
2. Number of samples in different regions around South Africa
3. XDR and TDR status of samples


Some questions you may want to consider:

* How has the prevalence of certain lineages or drug resistance changed over time? 
* are clusters/outbreaks happening in specific regions, or are they spreading throughout? Can we find close connections to countries outside of South Africa? 
* Are samples with high drug resistance all the same clone? Or are there multiple clones driving resistance?


Spend some time exploring these questions and the South African samples, both broadly across all samples and by looking at individual samples.


### Step 2:

Depending on what you have found in step 1, you might want to consider the following directions: 


1. With a group of other participants, each person can focus on collating lineage and drug resistant prevalence from South African in a single year. Then, as a group, you could compare to see how lineage prevalence and drug resistance has changed over time.

You can do this by using [this](metadata_spreadsheetSA) spreadsheet and a graphing application, such as Excel. 

2. Did you find any interesting clusters in the data? Take note of the isolate IDs for the cluster you are interested in, and download the raw reads from [ENA](https://www.ebi.ac.uk/ena/browser/home). Once you have the raw reads, you could investigate the real SNP distances between the samples using a separate tool (such as those within the Galaxy platform). You might also want to take note of associated metadata, including location, collection date and drug resistance when analysing your samples. You can access all sample metadata [here](metadata_spreadsheetSA).

**Discussion point:** What _Atlas_ distance would you expect for isolates that were clonally related? How do you expect this to differ when generating the real SNP distance? 




## Scenario 2: Outbreaks in South America

multidrug-resistant tuberculosis (MDR TB) emerged in Argentina in the early 1990's, as a result of the growing HIV epidemic. Since then, strains of MDR and XDR TB have continued to spread, particularly among HIV-infected patients. 

In this scenario, you will focus more on individual strains and clusters, looking to find outbreaks and evidence for spread throughout South America and globally. 


### Step 1: 

Explore the samples in Argentina. What are the common resistance profiles? Are there clusters that are only within Argentina? Are there others isolates that look like they have close relatives from different countries? 


### Step 2: 

Depending on what you find in step 1, you may want to consider the following directions: 

1. How many Argentinian samples are XDR? Are they related to each other? Is there evidence they are closely related to other samples outside of Argentina? For this, the best approach would be to find the XDR Argentinian isolates, record the isolate IDs and download the raw data from the [ENA](https://www.ebi.ac.uk/ena/browser/home). Once you have the raw reads, you could investigate the real SNP distances between the samples using a separate tool (such as those within the Galaxy platform). You can also explore whether these samples are related to other global samples using the Atlas derived distances. 

2. How much do the resistance profiles correlate with isolate distance? Does this indicate transmission of a single clone, or spontaneous mutants arising in different clones? When looking at the data, take note of the drug resistance profile you're interested in and the sample lineages. You may also wish to download a few samples from the [ENA](https://www.ebi.ac.uk/ena/browser/home) to determine the read SNP distance between the samples. 

 
 
## Scenario 3: Following the Mutation
 
Diagnostic tools to rapidly determine Tuberculosis drug sensitivity have been very important in the management and treatment of TB in high prevalence regions. However, these assays are usually designed around a set of known resistance markers, where new mutations conferring resistance may be missed. One particular mutation was spreading in Swaziland, South Africa, for many years and was missed because it was not included on the line probe assay. 

For this scenario, you will be investigating this SNP and looking to see how far it spread and if this was expansion of a single clone, or spontaneous mutations arising in many dfferent lineages. 

### Step 1: 

Perform a quick literature search to find what the mutation is that was causing rifampicin resistance in Swaziland but was missed by the line probe assay.

### Step 2: 

Once you know what the SNP is, perform a search for it in Atlas. Once you know which samples contain the SNP, explore these samples on Atlas to see how geographically spread they are, and if there is evidence of clonal expansion or spontaneous mutation. You may want to consider both the lineage assignment of samples and the isolate distances determined by Atlas. 

If you find a particular cluster you would like to interrogate further, take note of the isolate ID and download the raw data from the [ENA](https://www.ebi.ac.uk/ena/browser/home). Once you have the raw reads, you could investigate the real SNP distances between the samples using a separate tool (such as those within the Galaxy platform).


