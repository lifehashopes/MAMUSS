# MAMUSS
(Ma)rker (Mu)tation based (S)ARS-CoV-2 variant surveillance in (S)ewage - MAMUSS, is a marker mutation based apporach for varaint analysis in sewage. 

**Input**

1)Reference Mutation Profile for each variant  
  Download the current variant surveillance database from GISAID (https://www.epicov.org). To get the access to the database file, you need to register on      
  GISAID. After successful registration, file is available to download.
  
2)Variant caller file for each wastewater sample
  Tab seperated SnpEff output. This file contain mutations detected in each sample along with genomic position of each mutation, allele frequency,read depth. An example output file  having the following columns:
  
![image](https://user-images.githubusercontent.com/40615349/208083412-9c86c466-917e-49f2-8446-ca3002aecd70.png)


**Data Anaylsis**
1) Creation of the reference database from downloaded variant surveillance database. 
2) Determination of the SARS-CoV-2 variants in the wastewater sample.
