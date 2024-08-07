# Market Efficiency Analysis - AMD

This repository contains the analysis of the market efficiency for the security AMD, assigned as part of the SAPM assignment. The analysis covers three main aspects:

1. Weak form of Efficient Market Hypothesis (EMH)
2. Post earnings announcement drift
3. January effect

The data used for this analysis spans from 1st January 2021 to 31st December 2021. The deliverables are organized in an Excel file with multiple sheets, each dedicated to a specific part of the analysis.

## File Structure

- **Market Efficiency.xlsx**: The main file containing all the data and results of the analysis.

## Sheets Description

### 1. Top Sheet

This sheet contains the summary information and identification details of the assignment, including the author’s name and the topic of the assignment.

### 2. Weak EMH

This sheet contains the data and calculations for testing the weak form of market efficiency using the Runs test. The columns include:

- `Date`: Trading dates
- `Close`: Closing prices of AMD
- `Returns`: Daily returns of AMD
- `Returns t-1`: Previous day returns
- `Price Change`: Indicator of price increase or decrease
- `Count Runs`: Run count for the Runs test
- `Runs`, `n1`, `n2`, `n`, `E(runs)`, `Numerator`: Calculations for the Runs test

### 3. Event 1 to Event 4

Each of these sheets corresponds to a different earnings announcement event and contains the following information:

- `Intercept`: Intercept value from regression analysis
- `Beta`: Beta coefficient
- `R-Squared`: R-squared value of the regression
- `Std.Error`: Standard error of the estimate
- `Actual (Billion $)`: Actual earnings in billions
- `Estimated (Billion $)`: Estimated earnings in billions
- `Date`: Date of the earnings announcement
- Analysis conclusion: Whether there was a positive or negative surprise
- Link: URL to the media article used for comparison

### 4. Jan Effect

This sheet contains the analysis of the January effect by comparing the monthly returns for January to other months. The columns include:

- `Month`: Name of the month
- `First Day Price`: Opening price of the first day of the month
- `Last Day Price`: Closing price of the last day of the month
- `Returns (%)`: Monthly returns in percentage
- `Jan Returns`: Returns for the month of January
- `Other month returns`: Returns for other months
- `December 2020 returns`: Returns for December 2020 for comparison

## Summary of Results

A summary of the results can be found in the "Top Sheet" tab of the Excel file. The key findings include:

1. **Weak EMH**: Results from the Runs test indicate whether the market for AMD follows the weak form of EMH.
2. **Post Earnings Drift**: The event studies reveal the presence of any post earnings announcement drift.
3. **January Effect**: Comparison of January returns with other months to check for the January effect.

## How to Use

1. Download the `Market Efficiency.xlsx` file.
2. Open the file using any spreadsheet software (e.g., Microsoft Excel, Google Sheets).
3. Navigate through the sheets to explore the data and results for each part of the analysis.

## Conclusion

This analysis provides insights into the market efficiency of AMD using historical price data and earnings announcements. The findings can be useful for understanding market behavior and making informed investment decisions.
