Great Britain Insulation Scheme (GIBS) - A Data Story
This repository contains a deep-dive analysis into the Great Britain Insulation Scheme (GIBS), a UK government initiative designed to help households with the cost of insulating their homes.

I read that every Data Scientist is a storyteller, and that's what I tried to do here - tell a story with data!

The goal of this project was to go beyond simple reporting and use a multi-faceted dataset to answer key questions about the scheme's performance, its reach, and the key drivers of its success.

🎯 The Objectives: Answering the Key Questions
The analysis was designed to answer several core strategic questions:

How has the scheme's rollout progressed over time?

Which eligibility groups are benefiting the most?

What are the most common types of energy efficiency measures being installed?

What is the relationship between the number of households in a region and the uptake of the scheme?

Which property types and tenures are seeing the most upgrades?

📦 The Data
The analysis is based on the official Great Britain Insulation Scheme dataset, published by the Department for Energy Security and Net Zero and provided by Ofgem.

Source: data.gov.uk

Format: Multiple .xlsx files, each covering a different aspect of the scheme (monthly installations, measure types, regional data, etc.).

Size: The core dataset contains over 125,000 household records.

🛠️ Methodology & Workflow
The project followed a structured, end-to-end analytical process:

Data Sourcing & Cleaning: The multiple Excel files were ingested using Pandas. A significant part of the initial work involved robust data cleaning, which included renaming columns for clarity, handling unwanted summary rows that could distort the analysis, and ensuring all data types were correct for numerical and statistical analysis.

Exploratory Data Analysis (EDA): I used a combination of Pandas for statistical summaries and Matplotlib/Seaborn for visualization to explore the data, identify initial trends, and form hypotheses.

Insight Generation & Storytelling: The core of the project was to create a series of clear, compelling visualizations, each designed to answer one of the key objectives and contribute to the overall narrative of the scheme's performance.

📊 Key Findings & Visualizations
1. The Scheme is Accelerating, Driven by Low-Income Support
A time-series analysis shows that while the scheme had a steady start, the number of measures installed has seen a dramatic increase since early 2024. A stacked plot reveals that this growth is overwhelmingly driven by the Low Income Eligibility group, proving the scheme is successfully targeting its primary audience.

<p align="center"><i>Monthly measures installed, broken down by eligibility category.</i></p>

2. Insulation is the Core Focus
Analysis of the measure types shows that Cavity Wall Insulation (43.7%) and Loft Insulation (27.6%) together account for over 70% of all installations. This highlights a clear strategic focus on the most impactful insulation measures.

3. Eligibility, Not Population, Drives Uptake
A fascinating insight came from analyzing the parliamentary constituency data. A correlation analysis revealed a weak negative correlation between the number of households in a region and the number of measures installed. This proves that the scheme's success is not simply a function of population density; it is being driven by the successful targeting of specific eligibility groups.

4. Houses & Owner-Occupiers Benefit the Most
Analysis of property and tenure data shows a clear trend: houses (as opposed to flats or maisonettes) and owner-occupied properties are consistently receiving the highest number of upgrades, with a sharp increase in early 2024.

💡 Conclusions & Recommendations
This data-driven story reveals a successful and accelerating government initiative.

Key Conclusions:

The scheme is highly effective and its reach is growing exponentially.

It is successfully targeting its primary audience: low-income households.

The focus is correctly placed on high-impact insulation measures.

Success is driven by strategic targeting, not just population size.

Recommendation:

The significant increase in measures and upgrades clearly demonstrates the effectiveness of this scheme. **Expanding its reach to cover every corner of the country will further enhance
