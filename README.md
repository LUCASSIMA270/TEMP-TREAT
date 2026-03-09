# TEMP-TREAT
🌡️ TEMP-TREAT: Temperature & Child Maltreatment
Replicating Evans, Gazze, & Schaller (2025): The Impact of Heat on Child Welfare

This repository contains the replication and analysis of the paper "Temperature and Maltreatment of Young Children" (published in Review of Economics and Statistics, 2025). The project explores how short-term weather variations, particularly extreme heat, influence alleged and substantiated cases of child maltreatment across the United States.
🧐 The Research Question

Does extreme temperature affect the safety of young children? While poverty and substance abuse are known risk factors, this study investigates contemporaneous environmental shocks. We specifically analyze whether heat triggers aggression or leads to neglect through changes in parental time use and cognitive function.
🛠️ The Analytical Framework

The project utilizes a high-dimensional fixed effects model to isolate the causal impact of temperature:

    The Data: Combines the NCANDS (National Child Abuse and Neglect Data System) child welfare records with PRISM modeled daily weather data (2006–2016).

    The Methodology: Exploits within-county variation across years to control for local seasonality and state-level policy changes.

    The "Bins" Approach: Temperature is categorized into 5-degree Celsius bins (from ≤0∘C to >35∘C) to capture non-linear effects.

📂 Repository Contents

    Evans_2025_REStat.pdf: The core research paper being replicated, focusing on children aged 0-4.

    PRESENTATION_SIMATOVIC_HEDROUG.odp: The summary slide deck for the project, detailing the empirical strategy and findings.

    analysis_scripts/: (Placeholder for your R scripts) Including data cleaning, fixed-effects regressions, and visualization of the temperature gradient.

    outputs/: Regression tables and figures illustrating the "Neglect vs. Physical Abuse" results.

📈 Key Findings & Insights

    Heat & Neglect: An additional day of extreme heat (>35∘C) increases substantiated maltreatment by 0.5%. The effect is driven by neglect, not physical abuse.

    Mechanisms: Time-use data shows a significant decrease in active childcare during hot days.

    The AC Shield: There is evidence that high air conditioning penetration mitigates the adverse effects of heat on child welfare.

    Climate Forecast: Projections suggest that climate change could increase annual child victimization by 1.53% by 2100.

🚀 How to Run the Analysis

    Clone the repo.

    Environment Setup: Ensure R packages fixest, tidyverse, and PRISM are installed.

    Run Pipeline: Execute the main script to reproduce the Allegation and Victimization rate plots (replicating Figure 1 of the paper).
