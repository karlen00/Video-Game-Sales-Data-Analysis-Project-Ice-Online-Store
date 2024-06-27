# Video Game Sales Data Analysis Project for "Ice" Online Store

## Project Description

This project aims to identify patterns that determine the success of a video game based on sales data, user and critic reviews, genre, platform, and historical sales data. Through this analysis, we can identify the most promising games and plan more effective advertising campaigns for 2017.

## Dataset

The dataset used is from 2016 and contains the following information:

- `Name`: Name of the game
- `Platform`: Game platform (e.g., Xbox, PlayStation)
- `Year_of_Release`: Year of game release
- `Genre`: Game genre
- `NA_sales`: Sales in North America (in millions USD)
- `EU_sales`: Sales in Europe (in millions USD)
- `JP_sales`: Sales in Japan (in millions USD)
- `Other_sales`: Sales in other countries (in millions USD)
- `Critic_Score`: Critic review score (maximum 100)
- `User_Score`: User review score (maximum 10)
- `Rating`: ESRB rating (e.g., E, T, M)

## Analysis Steps

### Step 1: Load and Understand the Data

- Open the data file `/datasets/games.csv`.
- Study the general information from the existing data.

### Step 2: Prepare the Data

- Rename columns to lowercase.
- Convert data to appropriate data types.
- Describe the data type changes and the reasons behind them.
- Handle missing values:
  - Explain why you fill in or leave the missing values.
  - Provide possible reasons why these values are missing.
- Handle TBD (to be determined) cases.
- Calculate total global sales for each game and add a new column.

### Step 3: Analyze the Data

- Count the number of games released per year.
- Analyze sales variation by platform.
- Identify the platform with the highest total sales and analyze its sales distribution by year.
- Determine the data period for building the 2017 model.
- Analyze sales by platform: which platforms have the highest sales, which are growing or shrinking.
- Create a boxplot for global game sales by platform.
- Analyze how user and critic reviews affect sales on a popular platform.
- Compare sales of the same game on different platforms.
- Analyze the distribution of games by genre and identify the most profitable genres.

### Step 4: User Profiling by Region

- Identify the top 5 platforms for NA, EU, and JP regions.
- Identify the top 5 genres for NA, EU, and JP regions.
- Analyze the impact of ESRB ratings on sales in each region.

### Step 5: Hypothesis Testing

- Test the hypotheses:
  - The average user rating for Xbox One and PC platforms is the same.
  - The average user rating for Action and Sports genres is different.
- Determine the alpha threshold value.
- Explain the formulation of the null and alternative hypotheses.
- Explain the significance level chosen and the reasons behind it.

### Step 6: General Conclusions

- Write the overall conclusions from the analysis.

## Format and Writing

- Complete this task in a Jupyter Notebook.
- Insert programming code in code cells.
- Insert explanatory text in markdown cells.
- Apply proper formatting and add titles to each analysis section.

---

This README will guide you through the systematic and structured completion of the video game sales data analysis project for the "Ice" online store.
