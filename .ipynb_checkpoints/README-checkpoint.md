# Analysis of NYC School Zone Speed Camera data set - 2004 
This repository contains data, analytic code and findings that support portions of the article, "[School zone speed cameras not a deterrent for worst repeat offenders](https://docs.google.com/document/d/1Luh9gk2ol8IDU_q2-kB7ZIDpLwF5prlDB-y5a8IrNkE/edit?usp=sharing)," published April 18, 2024. Please read that article, which contains important context and details, before proceeding.
### Data
This analysis uses two spreadsheets with data from NYC Open Data.
- Open_Parking_and_Camera_Violations_20250417 (1).csv
- top_200_school_zone_speed_plates.csv

### Methodology
The notebook `Speed_zone_data.ipynb` performs three analyses:

Part 1: Collect all of the tickets issued for speeding in a school zone in New York City in 2024. This was filtered to New York license plates registered to passenger vehicles. 

Part 2: Perform `.value_counts()` of each license plate in descending order.

Part 3: Sort to 200 license plates that were issued the most tickets for speeding in a school zone.

### Outputs

The results of "Part 3" above are saved as `../Output/top_200_school_zone_speed_plates.csv`

### Running the analysis yourself

You can run the analysis yourself. To do so, you'll need the following installed on your computer:

- Python 3

### Licensing
 The data file in the output/ directory is available under the Creative Commons Zero v1.0 Universal license. All files in the data/ directory are released into the public domain.

  
### Feedback/Questions?
  Contact Cristina Ledra at cristina.ledra74@journalism.cuny.edu
