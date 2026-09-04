# Regulatory Query Intelligence Platform

An end-to-end regulatory query intelligence solution combining machine learning, NLP, Excel/VBA automation, and Power BI to automate query categorization and enable data-driven analysis.

## Overview

The project focused on automating the categorization and analysis of regulatory deficiency/query data.

Multiple machine learning and NLP approaches were evaluated to automatically classify regulatory queries into relevant categories and subcategories. The classification workflow was integrated with Excel-based automation using VBA macros, enabling automated processing of query information.

The resulting structured information was then used to develop an interactive Power BI dashboard for monitoring trends, exploring query patterns, and supporting decision-making.

## Project Workflow

Regulatory Query Data  
↓  
Data Preprocessing & Feature Engineering  
↓  
Text + Relevant Metadata  
↓  
NLP / Machine Learning Models  
↓  
Automated Category & Subcategory Classification  
↓  
Excel / VBA Workflow Automation  
↓  
Structured Analytical Dataset  
↓  
Power BI Dashboard  
↓  
Interactive Analysis & Reporting


                    ┌──────────────────────────────┐
                    │ Regulatory Query Data        │
                    │ Historical Deficiency Data  │
                    └──────────────┬───────────────┘
                                   │
                                   ▼
                    ┌──────────────────────────────┐
                    │ Data Preprocessing            │
                    │ • Cleaning                    │
                    │ • Text Preparation            │
                    │ • Feature Engineering         │
                    │ • CTD Metadata Integration    │
                    └──────────────┬───────────────┘
                                   │
                                   ▼
                    ┌──────────────────────────────┐
                    │ Text & Metadata Features      │
                    │ • TF-IDF                      │
                    │ • Representative Text         │
                    │ • CTD Sections                 │
                    │ • Regulatory Metadata          │
                    └──────────────┬───────────────┘
                                   │
                                   ▼
              ┌──────────────────────────────────────────┐
              │        ML / NLP Classification Layer     │
              │                                          │
              │  • Cosine Similarity                      │
              │  • SVM                                   │
              │  • Hierarchical SVM                      │
              │  • Word2Vec / TF-IDF Weighted Features  │
              │  • Confidence-Based Analysis             │
              └────────────────────┬─────────────────────┘
                                   │
                                   ▼
                    ┌──────────────────────────────┐
                    │ Automated Categorization     │
                    │                              │
                    │ Regulatory Query             │
                    │        ↓                     │
                    │ Category Prediction           │
                    │        ↓                     │
                    │ Category-Specific             │
                    │ Subcategory Prediction        │
                    └──────────────┬───────────────┘
                                   │
                                   ▼
                    ┌──────────────────────────────┐
                    │ Excel / VBA Automation       │
                    │ • ML Output Integration      │
                    │ • Automated Processing        │
                    │ • Structured Output           │
                    │ • Reduced Manual Effort      │
                    └──────────────┬───────────────┘
                                   │
                                   ▼
                    ┌──────────────────────────────┐
                    │ Analytical Dataset            │
                    │                              │
                    │ • Categories / Subcategories │
                    │ • CTD Sections                │
                    │ • Products                    │
                    │ • Geography                   │
                    │ • Trends / Status             │
                    └──────────────┬───────────────┘
                                   │
                                   ▼
                    ┌──────────────────────────────┐
                    │ Power BI Dashboard             │
                    │                              │
                    │ • Overview                    │
                    │ • Query Details               │
                    │ • TS / Aseptic                │
                    │ • CMC Trends                  │
                    │ • Metrics Explorer            │
                    └──────────────────────────────┘

## Key Contributions

### Machine Learning & NLP

- Evaluated multiple machine learning and NLP approaches for automated regulatory query categorization.
- Applied text-based feature engineering techniques for classification.
- Explored similarity-based and supervised classification approaches.
- Implemented hierarchical classification for predicting categories followed by category-specific subcategories.
- Incorporated relevant metadata alongside textual information to improve classification.

### Model Evaluation

- Compared multiple approaches including Cosine Similarity, SVM, Hierarchical SVM, Word2Vec, and TF-IDF-based methods.
- Evaluated model performance using unseen test data.
- Performed error analysis to identify common classification errors and areas for improvement.
- Conducted confidence-based analysis to understand prediction reliability.

### Excel & VBA Automation

- Integrated machine learning outputs into an Excel-based workflow.
- Developed VBA-based automation to streamline data processing and categorization.
- Reduced manual intervention by automating repetitive classification and data-handling tasks.
- Connected automated classification outputs with downstream reporting workflows.

### Power BI & Data Visualization

- Developed an interactive Power BI dashboard for regulatory query analysis.
- Created analytical views covering query volumes, categories, subcategories, trends, CTD sections, product information, geographic distribution, and action tracking.
- Implemented interactive filtering and exploration to allow users to analyze regulatory query information across multiple dimensions.
- Consolidated automated classification outputs into a centralized business intelligence reporting layer.

## Dashboard Sections

The reporting solution included multiple analytical perspectives:

- **Overview** — High-level query volumes, category distribution, geographic coverage, and key metrics.
- **Query Details** — Detailed query-level information and action tracking.
- **TS / Aseptic** — Analysis of relevant query classifications, CTD sections, product types, and related dimensions.
- **CMC Trends** — Trend analysis and distribution of regulatory queries across time and categories.
- **Metrics Explorer** — Interactive exploration of category, subcategory, and other project metrics.

## Technologies

- Python
- Pandas
- Scikit-learn
- NLP
- TF-IDF
- SVM
- Hierarchical Classification
- Word2Vec
- Excel
- VBA
- Power BI

## End-to-End Solution

The project combined machine learning, process automation, and business intelligence into a single workflow:

**Machine Learning**  
Automated regulatory query categorization.

**Process Automation**  
Excel/VBA automation for streamlined processing.

**Business Intelligence**  
Power BI dashboards for interactive analysis and reporting.

This provided an end-to-end workflow from raw query information through automated classification to visual analytics and decision support.

## Confidentiality Notice

This repository contains project documentation only.

The original implementation involved company-specific data, code, dashboards, and workflows that are not included in this repository due to confidentiality and proprietary information restrictions.

No proprietary datasets, source code, internal documents, or confidential company information are disclosed here.