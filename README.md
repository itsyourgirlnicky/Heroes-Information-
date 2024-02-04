# Pandas Data Cleaning Checkpoint

This checkpoint is designed to test your understanding of the content from the Pandas Data Cleaning Cumulative Lab.

Specifically, this will cover:

* Using pandas to filter data
* Using pandas to handle missing values
* Using matplotlib to create a graph using data from a dataframe

## Your Task: Analyze Superhero Eye Color

### Data Understanding

In this repository under the file path `data/heroes_information.csv` there is a CSV file containing information about various characters from superhero media properties.

The features of interest for this analysis will be:

`name`: The name (or AKA) of the character

`Eye color`: The eye color of the character

`Alignment`: "good", "bad", or "neutral". For the purposes of this analysis, we will only consider those with "good" alignment to be "superheroes"

### Requirements

#### 1. Filter Data to Relevant Columns

#### 2. Filter Data to Relevant Rows

#### 3. Drop Rows with Missing Values

#### 4. Find the Top 5 Most Common Eye Colors

#### 5. Plot a Bar Chart of Eye Colors

### Setup

In the cell below we import the relevant libraries, open up the CSV file as a dataframe called `df`, and convert cells containing `-` into cells containing `NaN` (because `-` was used to represent missing data in the original dataset).

***Hint:*** If you ever accidentally drop data that you didn't mean to drop, you can come back to this cell and re-run it to load a fresh copy of the data. Before submission, make sure you restart the kernel and run all of the cells to make sure that everything works in order.


