# GBM Market Segmentation Analysis – Technical Assessment
This project was completed as part of a technical assessment, where I was tasked with analyzing the structure of the Glioblastoma Multiforme (GBM) market to identify clinically meaningful patient sub-segments that are currently being treated differently. The goal of this analysis was to uncover distinct patterns and associations between patient characteristics and treatment plans, ultimately providing strategic insights and opportunities for our client.

The analysis involved deep exploratory data analysis (EDA), visualization, and statistical techniques to surface actionable insights. The hope is that these findings will guide internal discussions on how best to leverage this data to support more targeted and effective treatment strategies.

Before diving into the analysis, I ran data quality checks to ensure integrity. There were no null values or duplicate patient IDs, and I verified the validity of unique entries across all columns. The only exception was the “% of tumor mass surgically resected” column, which contained placeholder values (999) that were flagged for further handling.

This project demonstrates my ability to analyze complex medical datasets, uncover meaningful clinical insights, and deliver results that can inform strategic decision-making in the healthcare space.

## Dataset Overview
The dataset contains information on 750 GBM patients across 42 features, including:

## Patient demographics

Comorbidities

Age at diagnosis

Overexpressed/mutated genes

ECOG scores (measuring disease progression)

First- and second-line treatment regimens

## Summary of Findings
From the numerical analysis, I found that Avastin mono, Lomustine mono, and TMZ mono are the top three treatments chosen for middle-aged patients. Exploring the relationships between gene mutations, ECOG scores, and treatment options revealed that Lomustine mono and Avastin mono are commonly prescribed when patients have mutations occurring at a moderate frequency, regardless of race.

After careful feature selection, I built a K-Prototypes clustering system to segment patients into 27 distinct sub-groups, each exhibiting different treatment patterns. These sub-segments represent unique opportunities to invest in specific treatments tailored to the needs of different patient profiles.

Looking ahead, there is significant potential to apply supervised learning models to this data to predict treatment plans using the features identified through this analysis.
