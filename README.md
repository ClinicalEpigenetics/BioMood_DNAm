# BioMood_DNAm

This repository contains the code and analysis scripts used for the BioMood methylation study, a pilot study designed to explore potential epigenetic associations between DNA methylation markers in blood and adherence to a MD in pregnancy, using samples from the ORIGINS BioMood study.

Principal investigator: Dr David Martino, David.Martino@thekids.org.au
Project lead: Grace Tavelli and Nikki Schultz, nikki.schultz@thekids.org.au

## Project Overview

This project aimed to:

   * Conduct genome-wide differential methylation analyses to identify epigenetic variations between the study groups.
   * Perform replication and look-up analysis of previously identified differentially methylated CpGs in high MDA groups vs low MDA groups
   * Explored potential associations between blood methylation patterns and circulating in-flammatory markers (GlycA, GlycB and SPC) previously observed to exhibit differen-tial abundance in the same cohort of       women. 

## Data

Participants included in the BioMood study were nested within the ORIGINS parent cohort, a longitudinal study of family health outcomes, commencing in pregnancy. The present study utilized available whole blood samples collected at the 36-week of pregnancy time-point from eligible mothers. The BioMood study entry criteria have been previously published (Rowley et al, 2023). The pregnant women who were recruited to the BioMood study comprised women who had completed a modified 13-item Med-iterranean Diet Questionnaire (MDQ) twice during pregnancy with scores that varied by no more than 2 points. A total of 52 women met eligibility criteria, which included 25 control participants within the Low Mediterranean Diet Adherence (LMDA) group (an MDQ score equal to or less than 4 at 2 timepoints) and 27 case participants within the High Mediterranean Diet Adherence (HMDA) group (an MDQ score equal to or greater than 8 at 2 timepoints). 

## Analysis

The data analysis included the following steps:

    Raw (aligned) data processing and marker QC: 01.Data_processing.Rmd
    Sample QC, PCA and annotation: 02.Sample_QC.Rmd
    Hypothesis tesing of MD groups + replication analyis: 03.HypothesisTesting_MDA.Rmd
    Hypothesis testing of metabolites: 04.HypothesisTesting_Metabolites.Rmd

## References

Rowley, C. E.;  Lodge, S.;  Egan, S.;  Itsiopoulos, C.;  Christophersen, C. T.;  Silva, D.;  Kicic-Starcevich, E.;  O'Sullivan, T. A.;  Wist, J.;  Nicholson, J.;  Frost, G.;  Holmes, E.; D'Vaz, N., Altered dietary behaviour during pregnancy impacts systemic metabolic phenotypes. Front Nutr 2023, 10, 1230480.

For questions or feedback, please contact the corresponding author: David.Martino@thekids.org.au
