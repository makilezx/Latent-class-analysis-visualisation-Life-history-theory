# Latent class analysis & visualisation [Life history theory and basic personality traits]


*Utilizing insights from a 2020. scientific study, this repository delves into the intriguing intersection of Life History Theory (LHT) and the K-SF-42 questionnaire.*


## Introduction

Within the expansive landscape of the psychology of individual differences, Life History Theory (LHT) has emerged as a pivotal framework. Rooted in evolutionary biology, this theory has been shown, through previous research, to interconnect with various psychological constructs, notably personality traits.

## Aim

The primary goal of the analyses presented here is to explore latent classes within the context of LHT and investigate their relationships with fundamental personality traits. 


## Data

Sample consisted of 1049 participants . Of the total number of participants, 61.7% were male, while the age of the participants ranged from 17 to 85 years (M = 38.05; SD = 14.87).

Before analysis, the dataset underwent cleaning and preprocessing. Univariate and multivariate outliers were removed, and missing data were imputed using the Expectation-Maximization (EM) algorithm. Prior to that, Little's test was conducted to ensure the adequacy of the imputation process and the reliability of the dataset for subsequent analyses.

## Analysis Method

Summation scores were computed utilizing the R *psych* package. The code also performs calculations of Cronbach's alpha coefficients across questionnaire scales.

Subsequently, the code in this repository utilizes latent class analysis (LCA) to reveal distinct groups or subtypes of subjects based on their response patterns.

Additional analyses involve MANOVA to comprehensively understand group differences and the Games-Howell test for post hoc examinations. Also, the code visualizes *the predictive power* of personality types versus personality dimensions, employing R for analyses and Python (matplotlib) for visualizations (pictures 2 and 3). 

Tableau has been integrated for supplementary visualizations, particularly in illustrating clustering (picture 1).

## Results

Utilizing K-SF-42 questionnaire scores, the latent class analysis (LCA) reveals the identification of five distinct classes: Moderate LHT; High parental relationship quality; *Slow LHT; Low parental relationship quality; Slow LHT – low romantic partner attachment quality*.
 
###### Picture 1: latent classes extracted by LCA
![Picture1](https://github.com/makilezx/Latent-class-analysis-visualisation-Life-history-theory/assets/50851469/77463bcb-8631-40fc-a2bd-aed9d552b052)
###### Picture 2 and 3: predictive power of personality types vs personality dimensions
![Picture3](https://github.com/makilezx/Latent-class-analysis-visualisation-Life-history-theory/assets/50851469/1bfbd184-0994-41d1-b6a9-47cb1221a42b)
![Picture2](https://github.com/makilezx/Latent-class-analysis-visualisation-Life-history-theory/assets/50851469/f63f1c01-f030-4f6e-b7fd-095c0e3defb2)

