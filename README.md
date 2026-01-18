# Indian-Election-Data-Visualization-Dashboard-1962--2019-

Interactive Tableau dashboard analyzing Indian Lok Sabha election outcomes from 1962–2019, designed to make multi-decade comparisons clear and consistent by focusing on the top five parties by cumulative votes.

## Project Goals
- Analyze long-term shifts in party dominance across six decades.
- Compare vote share distributions by gender across major parties.
- Measure how candidate loyalty (loyal vs. turncoat) relates to win rates over time.
- Explore how turnout and vote share connect to victory margins across constituency types (General/SC/ST).

## Dataset
- Dataset: 'India-TCPDGEall2020-12-14' (Indian Lok Sabha elections, 1962–2019; all states/UTs).
- Size: 91,399 rows × 42 columns.
- Note: The dataset is not included in this repository because it is third-party data. Download it from the official source and place it locally before opening the workbook. 

## Data Preparation
- Performed cleaning and standardization steps to improve analytical quality:
- Dropped 13 columns due to missing values or limited analytical value.
- Standardized party naming (e.g., 'B.J.P.' → 'BJP').
- Corrected rows with misplaced data to ensure accuracy.

## Tableau Calculated Fields
This workbook uses multiple calculated fields to derive analysis-ready metrics and comparisons.

- Decades: Buckets election years into 1960s–2010s for time-based comparisons.
- Win: Binary flag indicating whether a candidate won the seat.
- Party Top 5: Filters records to the top five parties by cumulative votes (1962–2019).
- Turncoat Win Rate: Win rate for candidates who switched parties.
- Loyal Win Rate: Win rate for candidates who did not switch parties.
  
## How to View / Run
1. Download the dataset from the official source (not included in this repo).
2. Open the Tableau workbook file: `Dashboard_Final.twb'.
3. If Tableau prompts for a missing data source, use **Edit Connection** / **Replace Data Source** and point Tableau to the downloaded dataset file.
4. Open the dashboard tab to interact with filters/highlights across tasks.
