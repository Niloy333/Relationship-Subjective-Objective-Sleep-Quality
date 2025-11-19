# Relationship-Subjective-Objective-Sleep-Quality

## Overview

In this study, we will address the following research questions:

1. How well do subjective sleep quality (reported by participants) and objective sleep quality<sup>*</sup> (measured from their sleep EEG data) correlate within a single subject?
2. How well do subjective sleep quality and objective sleep quality correlate across subjects?
3. How well do specific objective measures of sleep quality predict subjective sleep quality?

<sup>*</sup>Objective sleep quality is a complex phenomenon and currently lacks a universally established definition. In this study, we will use total sleep time (TST), sleep onset latency (SOL), wake after sleep onset (WASO), and sleep efficiency (SE) as measures that individually represent objective sleep quality. These terms are defined as follows:	
 - TST: The total duration (in minutes) spent asleep during the period between the first and last non-wake epochs. In this study, we will use 30-second epochs for sleep scoring.
 - SOL: The time (in minutes) between lying down on the bed and achieving the first non-wake epoch.
 - WASO: Total duration (in minutes) spent awake between the first and last non-wake epochs.
 - SE: The ratio of TST and total time (spent) in bed or TIB.

## Data

We will use two datasets to answer these research questions: one from a longitudinal single-subject study and one from an extensive multi-subject cohort study. The single-subject study, titled [Quantified Scientist (QSci)](https://doi.org/10.13140/RG.2.2.30420.41606), includes (among other data) wearable-based sleep recordings and the participant’s subjective sleep quality over a period of 6+ years. In this study, we will derive objective sleep quality metrics primarily from overnight EEG recordings obtained with the Zmax headband. However, the participant also wore other wearables (often simultaneously), including the Dreem2 headband and the Oura Ring, to record sleep; and, in the event of missing or unusable Zmax data, the OSQ metrics can be derived (or estimated) from these wearables. The participant reported his subjective sleep quality the following morning by completing a questionnaire. This dataset will reflect the interplay between subjective and objective sleep quality in a within-subject design.

The multi-subject study, titled the [Healthy Brain Study (HBS)](https://doi.org/10.1371/journal.pone.0260952), is a longitudinal study conducted by multiple research centers based at Radboud University, Nijmegen, the Netherlands. HBS is one of the most extensive studies to date involving healthy participants. The researchers collected extensive physical, mental, behavioral, and cognitive data from over 850 participants (aged 30 to 39) from the Greater Nijmegen region, representing diverse educational and financial backgrounds. However, in this study, we will use only sleep EEG recordings (for objective sleep quality measures) and participants’ responses to the Pittsburgh Sleep Quality Index (PSQI). Participants’ overnight sleep was monitored using the Zmax headband for three weeks (three one-week segments), and they filled in the PSQI questionnaire after each week of monitoring. Data collection took place between September 2019 and December 2023, and each participant was monitored for 1–1.5 years. Out of the over 850 participants who took part in the study, ≈720 continued for the entire three weeks, and we (primarily) aim to include only those participants in our analysis. This HBS will reflect the interplay between subjective and objective sleep quality across different subjects. No new data will be collected for the study.

## Mock Analysis

The folder [*Preregistration_analyses_with_mock_data*](https://github.com/Niloy333/Relationship-Subjective-Objective-Sleep-Quality/tree/base/Preregistration_analyses_with_mock_data) contains the planned analyses on synthetic data. Please note that the results presented in these notebooks are not the project's actual outcomes; instead, they serve as a sketch of the analyses outlined in the project's preregistration.

## Reference

A preregistration document with more details on the project will be added soon.

**The project is currently in progress, and more details will be added once it is complete.**
