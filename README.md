# Analysis of most deadly earthquakes (data question:3)

### This project was a team-based excercise at NSS. 
### Team Members: 
- Ashutosh Singhal
- Racheal Abram
- Bernes Karacay

## Questions:
- Nate Silver discusses the difficulty of predicting earthquakes in The Signal and the Noise, but are there factors that make an earthquake more likely?
- Are there factors that make an earthquake more deadly?
- Where would you live if you wanted to eliminate the risk of experiencing an earthquake?
- Where would you avoid living?

## Method:
- Read the table of earthquakes from https://en.wikipedia.org/wiki/List_of_deadly_earthquakes_since_1900 using beautifulsoup and load it to a pandas dataframe. An introduction to the request and beautifulsoup libraries is provided in TuringAward_soup.ipynb.

### Data cleaning tasks include:
- Replace empty strings with NaN
- Remove the footnotes from the 'Other Source Deaths' column
- Convert Magnitude to a numeric
- Create a new column ('deaths') that evaluates the four total-death columns ('PDE Total Deaths', 'Utsu Total Deaths', 'EM-DAT - Total Deaths', and 'Other Source Deaths') and populates the new column with the highest value.
- Explore the data in terms of when and where earthquakes occurred and how severe they were (magnitude, deaths, secondary effects).
- Feel free to try out various visualization tools. 
