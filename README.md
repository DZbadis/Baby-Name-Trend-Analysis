# 👶 Baby Name Trend Analysis (SQL Project)

This project explores baby name trends across the United States using SQL. The dataset includes information on names, gender, state, year, and number of births. The objective was to uncover trends and patterns in baby name popularity, comparing them over time, regions, and by uniqueness.

## 🧠 Objectives & Tasks

### 📈 1. Track Changes in Name Popularity
- Identify the **overall most popular** girl and boy names.
- Analyze how their **rankings changed over the years**.
- Detect names with the **biggest jumps in popularity** from the first to the last year.

### 📆 2. Compare Popularity Across Decades
- Find the **top 3 girl and boy names for each year**.
- Find the **top 3 girl and boy names for each decade**.

### 🌎 3. Compare Popularity Across Regions
- Count the **number of babies born** in each of the 6 U.S. regions.
- Identify the **top 3 girl and boy names per region**.
- 📌 Special case: Michigan (`MI`) is grouped with the **Midwest region**.

### 🧬 4. Explore Unique Names
- Find the **10 most popular androgynous names** (used for both genders).
- Detect the **shortest and longest names**, and the most popular ones within each.
- Find the **state with the highest percentage** of babies named `"Chris"`.

## 🗃️ Dataset
- Source: Maven Analytics Baby Names Dataset
- Contains: multiple tables : names & region

## 🛠️ Tools & Technologies
- SQL (MySQL)
- Beekeeper Studio
- GitHub

## 📊 Sample Analyses
- `"Emma"` and `"Liam"` were among the most popular names in recent years.
- Certain names surged in popularity (e.g., `"Aiden"`), while others faded.
- Regional trends showed distinct name preferences, like `"Jose"` in the Southwest.

## 📁 Files
- `baby_name_analysis.sql` – Main SQL file containing all queries grouped by objective.
- `region_mapping_note.txt` – Clarifies how states were grouped into regions.

## 📣 About This Project
This challenge was completed as part of a SQL portfolio series to demonstrate the ability to clean, transform, and analyze data using pure SQL logic.

