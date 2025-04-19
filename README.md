# Analysis of NYC School Zone Speed Camera data set - 2004 
This repository contains data, analytic code and findings that support portions of the article, "[School zone speed cameras not a deterrent for worst repeat offenders](https://docs.google.com/document/d/1Luh9gk2ol8IDU_q2-kB7ZIDpLwF5prlDB-y5a8IrNkE/edit?usp=sharing)," published April 18, 2024. Please read that article, which contains important context and details, before proceeding.
<h2>Data</h2>
This analysis uses two spreadsheets with data from NYC Open Data.
  <br>- Open_Parking_and_Camera_Violations_20250417 (1).csv
  <br>- top_200_school_zone_speed_plates.csv
  <h2>Methodology</h2>
  <br>The notebook Speed_zone_data.ipynb performs three analyses:
  <br> Part 1: Collect all of the tickets issued for speeding in a school zone in New York City in 2024. This was filtered to New York license plates registered to passenger vehicles. 
  <br>Part 2: Perform value count of each license plate in descending order.
<br>Part 3: Sort to 200 license plates that were issued the most tickets for speeding in a school zone.
  <h2>Outputs</h2>
The results of "Part 3" above are saved as top_200_school_zone_speed_plates.csv
  <h2>Running the analysis yourself</h2>
  <br>You can run the analysis yourself. To do so, you'll need the following installed on your computer:

<br>- Python 3
  <h2>Licensing</h2>
 The data file in the output/ directory is available under the Creative Commons Zero v1.0 Universal license. All files in the data/ directory are released into the public domain.
  <h2>Feedback/Questions?</h2>
  Contact Cristina Ledra at cristina.ledra74@journalism.cuny.edu
