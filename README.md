# fNIRS GLM Analysis 🧠📊
Welcome to the fNIRS GLM Analysis repository! 🎉🔍

## Overview 📝
This repository delves into the analysis of data from a real multichannel functional near-infrared spectroscopy (fNIRS) experiment, a non-invasive neuroimaging technique. 
The experiment consists of three conditions: tapping with the left hand, tapping with the right hand, and a control condition where the participant does nothing. 
The goal is to understand the neural activity associated with different tapping conditions using General Linear Model (GLM) analysis.

## General Linear Model (GLM) Analysis 📈
The General Linear Model (GLM) is a statistical approach commonly employed in neuroimaging to analyze the relationship between experimental conditions and observed neural responses. It is particularly well-suited for modeling complex experimental designs and investigating the impact of multiple factors on the measured data.

## Understanding GLM in Neuroimaging 🤔
In the context of neuroimaging, GLM is used to model the observed brain activity as a combination of different factors or experimental conditions. The model assumes that the measured responses are a linear combination of these factors, making it a powerful tool for examining the specific contributions of each condition.

## Key Components of GLM Analysis 🧩
- Design Matrix: A fundamental element of GLM analysis is the design matrix. It encapsulates the experimental conditions, their timings, and potential covariates. Each column in the matrix represents a different experimental factor.

- Model Fitting: GLM involves fitting the model to the observed data, estimating the parameters that best explain the variance in the neural responses. This step allows for the quantification of the effect of each experimental condition.

- Contrast Analysis: After fitting the model, contrast analysis is performed to identify significant differences between experimental conditions. This helps researchers pinpoint regions of the brain that exhibit distinct responses.

## Steps in GLM Analysis 🔄

Import raw NIRS data 📥
 - Begin by importing the raw NIRS data, which is essential for subsequent analysis steps.

 Clean up annotations before analysis 🧹
 - Ensure that annotations are accurate and well-prepared for precise analysis.

 Preprocess NIRS data 🛠️
 - Prepare and preprocess the NIRS data, enhancing its quality and suitability for analysis.

View experiment events 👁️
 - Explore the experiment events to gain insights into the temporal structure of the data.

Create design matrix 📊
 - Develop a design matrix, a fundamental component in GLM analysis that defines experimental conditions and their timing.

Examine expected response 🧐
 - Analyze the expected neural response to different tapping conditions based on the experimental design.

Fit GLM to subset of data and estimate response for each experimental condition 📈
 - Apply the GLM to a subset of data to estimate neural responses for each experimental condition.

Fit GLM to all data and view topographic distribution 🗺️
 - Extend GLM fitting to the entire dataset and visualize the topographic distribution of neural responses.

Analyze regions of interest 🔍
 - Zoom in on regions of interest for a detailed analysis, potentially revealing specific patterns of neural activity.

Compute contrasts 🔄
 - Calculate contrasts to highlight significant differences in neural activity between experimental conditions.

Export Results 📤
 - Export the results for further examination, sharing, or integration with other analyses.

Determine true and false positive rates 🎯
 - Evaluate the accuracy of the analysis by determining true and false positive rates, ensuring robust findings.

## Results 📊

The analysis provides:
- Topographic maps of response 🌎
- ROI timecourses and statistics 📈
- Contrast maps comparing conditions

This allows investigating the spatial patterns of brain activity involved in left vs. right hand tapping!

Feel free to explore each step and adapt the analysis to your specific needs. Contributions and feedback are highly appreciated! 🤝🚀
