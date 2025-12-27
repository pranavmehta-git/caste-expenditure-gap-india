# Caste-Based Household Expenditure Disparities in Uttar Pradesh

An analysis of caste-based economic inequality using the ACCESS 2018 survey data.

## Overview

This project examines disparities in household expenditure between "General" and "Reserved" (Scheduled Caste, Scheduled Tribe, Other Backward Class) caste groups in Uttar Pradesh, India. The analysis investigates the role of land ownership and educational attainment in explaining these gaps.

## Key Findings

- **Overall expenditure gap**: General caste households spend Rs. 1,385 more per month on average
- **Land ownership disparity**: General caste households are over-represented among landowners (33% of landowners vs. 24% of population)
- **Education effect**: The gap narrows to Rs. 473 among educated landowners, suggesting education helps reduce inequality
- **Persistence**: Gaps persist even after controlling for land ownership and education, indicating structural factors at play

## Data

This analysis uses the **ACCESS 2018** (All India Survey on Consumer Payment Systems) survey, focusing on the Uttar Pradesh subsample (n = 3,002 households).

**Note**: The `access2018.RData` file is required to run this analysis but is not included in this repository due to data sharing restrictions.

## Files

```
├── caste-expenditure-UP.Rmd    # Main R Markdown analysis
├── README.md                   # This file
├── .gitignore                  # Git ignore rules
└── LICENSE                     # MIT License
```

## Requirements

- R (≥ 4.0)
- R packages:
  - `tidyverse`
  - `DescTools`
  - `dplyr`

Install required packages:

```r
install.packages(c("tidyverse", "DescTools"))
```

## Usage

1. Place `access2018.RData` in the project root directory
2. Open `caste-expenditure-UP.Rmd` in RStudio
3. Knit to HTML or PDF

## Acknowledgments

This analysis was completed as part of the *Data Analysis for Policy Research using R* course at Columbia University, taught by **Prof. Harold Stolper**.

## License

MIT License - see [LICENSE](LICENSE) for details.

## Author

Pranav Mehta
