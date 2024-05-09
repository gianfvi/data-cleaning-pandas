# data-cleaning-pandas

### Eduardo Da Silva, Radley Joseph, Dylan Sedeno, Maya Wilson-Fernandez, Gian F. Villafañe

### Project Overview
  - The Python code is designed to focus primarily on data detailing global shark attacks and data based on NOAA's Marine Protected           Areas. 
  - It involves several key steps like extensive cleaning and formatting and the extraction of specific components like month and year        from dates. 
  - It modifies the data by categorizing months into seasons and refines the dataset by focusing on US based attacks only, and then           separating the data into provoked and unprovoked attacks. This also performs detailed analysis by grouping data to understand            seasonal trends and demographic patterns related to shark attacks.
  
## Problem Statement 
  Assessing the correlation between marine protected areas / shark sanctuaries and frequency of shark attacks on humans. 

## Hypotheses
- Hypothesis 1 - Shark attacks are less prevalent in Marine Protected Areas due to increased protections and more food sources.
- Hypothesis 2 - Unprovoked attacks are more prevalent in Marine Protected Areas.
- Hypothesis 3 - Shark attacks are more prevalent in warmer seasons like spring and summer. 

### Data Structuring - Example
- This code is designed to add a new column called 'seasons' to the dataset, which categorizes each shark attack by the season it           occurred in, based on existing date data.
- This process not only helps in structuring the data but also serves as a crucial step in cleaning and organizing the dataset

### Data Filtering - Examples
This code filters the DataFrame to include only the rows where the 'Type' column has values that are not equal to 'Provoked' in the first example, and 'Unprovoked' in the second example.
This is done to isolate the data containing the unprovoked shark attacks in order to prove the hypothesis. 

## Sources
- NOAA. (n.d.). The MPA Inventory. The MPA Inventory | National Marine Protected Areas Center. https://marineprotectedareas.noaa.gov/dataanalysis/mpainventory/ 
- Shark Research Institute. (n.d.). Incident Log. Retrieved from https://www.sharkattackfile.net/incidentlog.htm
