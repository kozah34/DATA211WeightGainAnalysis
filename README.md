# DATA 211: Calorie Intake and Weight Gain Analysis

## Overview
This repository contains the final project for DATA 211, submitted by Derrick Nyagesuka. The project investigates whether increasing daily calorie intake from 2500 to 3500 calories for 7 days results in greater weight gain compared to maintaining 2500 calories for 7 days. Data was collected over 14 days (April 15–28, 2025), with weights measured daily and analyzed using a two-sample T-test in R. Visualization used is a line graph.

## Research Question
Does increasing my daily calorie intake from 2500 to 3500 calories for 7 days result in greater weight gain compared to maintaining 2500 calories for 7 days?

## Files
- **Data211Project.pptx**: PowerPoint presentation
- **weightGainData.csv**: Dataset (Day, Weight, Calories for 14 days).
- **DATA211FinalProject.Rmd**: R script for T-test and visualizations (line graph).
- **lineplot.png**: Line graph of daily weight over 14 days.
- **t_test_results.png**: T-test results (T-statistic, p-value, conclusion).

## Instructions
1. **View Presentation**: Open `Data211Project.pptx` to see the project overview, data, visualizations, T-test, and conclusion.
2. **Explore Data**: Open `weightGainData.csv` in a spreadsheet or R to view the 14-day weight and calorie data.
3. **Reproduce Analysis**:
   - Install R and RStudio.
   - Run `DATA211FinalProject.Rmd` to generate `lineplot.png`, and `t_test_results.png`.
4. **Check Results**

## Analysis
- **Data Collection**: Tracked weight (lbs) and calorie intake (2500 or 3500 calories) for 14 days. Days 1–7: 2500 calories (Normal); Days 8–14: 3500 calories (Increased).
- **Variables**: Dependent: Weight (lbs); Independent: Calorie Condition (Normal vs. Increased).
- **Analysis**: Two-sample, one-tailed Welch’s T-test in R to compare mean weights (H₀: μ_Increased = μ_Normal, H₁: μ_Increased > μ_Normal).
- **Visualizations**: Line graph (daily weight trend).
- **Conclusion**: Rejected H₀ (p = 0.0009715 < 0.05), confirming increased calorie intake leads to greater weight gain.
