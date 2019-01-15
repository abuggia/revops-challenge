# revops-challenge

Use the data found in data.csv to answer the questions below.  Please use Excel or Google sheets for analysis.  All work to derive answers should be found in worksheets in the form of formulas and static cell content.  Once importing data.csv into Excel or Google Sheets, the calculations used to derive answers should reference the raw data (or derivations) and should be "live." In other words if I were to change the imported data, the answers should automatically update.

## Source Data

The data is meant to represent simple sales funnel data or deal flows.  Each deal is associated with a company and can progress through the various sales stages: `S1`, `S2`, `S3`, `S4` and `WON`.  A deal can also be moved to from any of the `S` stages to `LOST`. There will be a row for each stage in the deal flow.  For each row, the stage will be different, the company name will be the same and the other fields may vary.  There will be a You can make the following assumptions about the data in data.csv

  1. Dates will progress in time with each stage in the deal flow.
  2. Amounts may vary from stage to stage.
  3. `WON` or `LOST` will always be the last stage in the flow.
  4. All deals start and end within 2018.  That is, for each company name, there will be a row for `S1` and a row for `WON` or `LOST` with a date in 2018.
  5. There is exactly one deal (flow through stages) for each company name.


## Questions
  1. How much total business was closed?
  4. What is the average ACV of deals closed in Q3?
  5. How many total WON deals were in each ACV bands: 50K-100K, 100K-250K, 250K-500K?


