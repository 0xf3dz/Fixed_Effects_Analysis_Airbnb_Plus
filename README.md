### README Description

This repository is a continuation of **Project 1**, where we explored the impact of Airbnb's Plus program on booking rates. Building on the prior analysis, this project refines the hypotheses and addresses previous limitations, such as unobserved factors and fixed effects.

In this second phase, we adopt a **Fixed Effects model** with cross-sectional and time-series dimensions. The analysis compares treated cities with control cities to determine the causal effect of the Plus program on two key metrics:
1. **Booking Rates** – The ratio of bookings to cancellations.
2. **Customer Satisfaction** – Measured by average listing reviews.

### Key Features
- **Data Cleaning & Preprocessing**: Handled missing values, treated outliers, and log-transformed price variables for robustness.
- **Difference-in-Differences (DiD) Analysis**: Assessed the impact of the Plus program pre- and post-implementation across multiple cities.
- **Fixed Effects Regression**: Isolated the program's influence from city-specific and time-specific factors.

### Findings
1. The Airbnb Plus program showed **no significant improvement** in booking rates.
2. The program was associated with a slight **decrease in customer satisfaction** due to elevated customer expectations.
3. Other factors, such as pricing, property age, and local employment rates, play significant roles in shaping outcomes.

### Contents
- **/data**: Preprocessed datasets used for analysis.
- **/code**: Python scripts for data cleaning, analysis, and visualization.
- **/results**: Output plots and regression tables.
- **/report**: Final paper detailing the methodology and findings.

### Future Directions
The analysis highlights opportunities to explore city-specific and seasonal factors that could enhance the program's success. Recommendations include piloting the Plus program in cities with:
- High employment rates,
- Relatively low listing prices,
- Abundant historical properties.
