# S-P500-Market-Analysis-and-Stock-Segmentation
A comprehensive stock market analysis and segmentation using Risk-Return analysis, RFM modelling, Ward Hierarchical Clustering and K-Means through a multi-layered quantitative approach, combining financial performance metrics, behavioral modeling to categorize equities into distinct, actionable investment profiles.
S&P 500 Stock Market Analysis and Segmentation

##Project Overview

This project analyses S&P 500 stocks using historical market data from 2021 to 2024. It applies risk–return analysis and Recency, Frequency and Monetary (RFM) modelling to identify groups of stocks with similar market behaviour and trading activity.

Objectives

Analyse historical stock performance and weekly returns.

Calculate beta to evaluate stock sensitivity to the S&P 500 benchmark.

Apply RFM analysis to measure recent high-volume trading activity.

Identify stock segments using Ward Hierarchical Clustering and K-Means.

Compare clustering results and examine sector composition.

Evaluate the effect of removing Monetary from the RFM model.

Key Findings

Two clusters were selected for both risk–return and RFM segmentation.

The risk–return clusters separated stocks with relatively higher and lower historical beta and weekly returns.

The RFM clusters identified groups with different levels of recent and frequent high-volume trading activity.

Ward and K-Means produced strong agreement, with an ARI of 0.9178 for risk–return clustering and 0.8639 for RFM clustering.

Removing Monetary from the Ward RFM model resulted in an ARI of 0.8572, indicating that most stock assignments remained similar.

Tools and Technologies

Python

Google Colab

Pandas and NumPy

Scikit-learn

SciPy

Matplotlib and Seaborn

Yahoo Finance

GitHub
