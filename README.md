# OpenTargets_drug_repositioning
The scripts in this repository perform the following tasks necessary for drug repositioning using Open Targets:

01 - search Open Targets for every gene associated to a list of diseases (here: PNDs - Psychiatric and Neurological Disorders);

02 - search Open Targets for every drug associated to a list of diseases (here: PNDs - Psychiatric and Neurological Disorders);

03 - detect genes that are exclusive to each diseases;

04 - search Open Targets for drugs that affect the disease-exclusive genes detected in 03;

05 - filter results from 04 to keep only drugs that:

a)affect genes that are coexpressed in the group of diseases (here: genes coexpressed in PNDs according to Gandal, 2018a);

b)affect only one gene among all searched genes;
      
