# Flatiron School Data Science Module 1 Project

Project Members: Aktan Abdygaziev and Bailey Bjornstad


## Project Goals

In this analysis, we aim to identify the best avenues for Microsoft's new movie department to pursue when creating new movies. We will attempt to identify broad trends in genre popularity and profitability, as well as identify those creators (directors, writers, etc.) who are particularly profitable.

### Some Guiding Questions

1. Which genre of movie offers the highest potential for profit?
  - Are there any trends in popularity and gross income over time by genre that we might want to be aware of?
  - Are there any genres that seem to have higher levels of long-lasting popularity? (So as to build engagement with this new Microsoft Movie branch)
2. How long does it take to break even, and are there trends in the return on investment?
3. Are there any movie crews that perform above average, and create movies with high popularity and income?
4. How are user reviews and critic reviews related? Are there any trends that seem to be mirrored in these separate categories?


## Methodology 

### Data Cleaning

The data will need to be cleaned. The interactive notebook [`data-cleaning.ipynb`](./data-cleaning.ipynb) holds the actual cleaning procedures. Cleaned data is also saved in the folder [`./cleaned_data/`](./cleaned_data), and analyzed data in the [`./analyzed_data/`](./analyzed_data) folder.

### Data Merging

After each dataset is cleaned, they will be ready for merging into our final dataset which can be used for analysis. The interactive notebook [`data-merging.ipynb`](./data-merging.ipynb) holds the merging procedures. The merged data is saved in the [`./cleaned_data/`](./cleaned_data) folder, as `final_data_merged.csv`.

### Data Analysis

After cleaning, the data will need analysis and visualization. The interactive notebook is [`data-analysis.ipynb`](./data-analysis.ipynb).

### Selected Visualizations and Conclusions

An interactive notebook with visualizations and conclusions targeted at a non-technical audience can be found at [`visualizations-and-conclusions.ipynb`](./visualizations-and-conclusions.ipynb). Moreover, the final plots can be found at [`plots`](plots) in PNG format.


## Data Sources

Microsoft has provided some data from IMDB, The Numbers.com.

All data lives in [`./data/`](./data) in CSV format.

- IMDB
  - data
    - imdb.name.basics.csv
    - imdb.title.basics.csv
    - imdb.title.crew.csv
    - imdb.title.principals.csv
    - imdb.title.ratings.csv
  - documentation
    - All data has come from https://www.imdb.com/interfaces/, just filtered to only 2010-2018 movies.
- The Numbers
  - data
    - tn.movie_budgets.csv
  - documentation
    - This comes straight from [The-Numbers.com](https://www.the-numbers.com/movie/budgets/all)
    - this includes all data from The Numbers! it is not subset to 2010-2018


## Project Checklist:

 - [x] Use data from at least two sources
   - [x] Establish naming conventions for variables and datasets
   - [x] Clean dataset & record parameters used to clean the data
     - [x] You may use Pandas or Python functions
     - [x] Document every step of the cleaning process
     - [x] Create at least two new features that were not present in the original data sets
 - [x] Use Pandas and Numpy to generate useful metrics for comparing films

 - [x] Posted to git repository:
   - [x] A README.md listing project members, goals, responsibilities, and a summary of the files in the repository
   - [x] At least 10 commits
     - [x] Must include short, descriptive commit messages
     - [x] Each project member should commit at least once
   - [x] A Jupyter notebook targeted to a technical audience that contains
     - [x] Clean and commented code so an independent party can replicate your analysis and justify your analytical choices
     - [x] Code should follow Pep8 standards
     - [x] Custom functions should be stored in .py file and imported whenever possible
   - [x] Your final joined and cleaned dataset that was used for analysis
   - [x] A narrative Jupyter notebook targeted to a non-technical audience that provides:
     - [x] The purpose of your analysis and why it matters
     - [x] 4 well annotated visualizations created using Matplotlib/Seaborn
     - [x] 2 meaningful summary tables using Pandas
     - [x] At least four actionable insights (What type of films should they be looking to produce? What should the budget requirements be? Should they recruit certain actors for their films?)
   - [x] A pdf of no more than 8 slides used in project presentation targeting non-technical audience
     - [x] Apply consistent and effective formatting to create a “professional” appearing deck
     - [x] Write an abbreviated high-level overview of methodology
     - [x] Justify at least 2 concrete recommendations 
     - [x] include exported visualizations from analysis
     - [x] Target the presentation to a non-technical audience, avoid jargon
     - [x] Take no more than 5 minutes to present
