# Netflix Dataset Analysis

![Netflix Logo](https://upload.wikimedia.org/wikipedia/commons/0/08/Netflix_2015_logo.svg)

## Project Overview
This project analyzes the Netflix dataset to uncover trends in content releases, genres, countries, and age groups. The goal is to provide **strategic insights** into Netflix's content distribution and viewing patterns. The analysis is performed using **Python**, **Pandas**, **Matplotlib**, **Seaborn**, and **Plotly**.

---

## Table of Contents
- [Technologies Used](#technologies--used)
- [Dataset](#dataset)
- [Features](#features)  
- [Data Cleaning & Feature Engineering](#data-cleaning--feature-engineering)  
- [Visualizations](#visualizations)  
- [Installation & Usage](#installation--usage)  
- [Folder Structure](#folder-structure)  
- [Author](#author)

---

## 🛠️ Technologies Used

This project uses the following tools and technologies:

| Category | Technologies |
|-----------|---------------|
| **Programming Language** | Python |
| **Data Handling & Analysis** | Pandas, NumPy |
| **Data Visualization** | Matplotlib, Seaborn, Plotly |
| **Text Visualization** | WordCloud |
| **Notebook Environment** | Google Colab / Jupyter Notebook |
| **Version Control** | Git & GitHub |
| **IDE / Editor** | Visual Studio Code |

---

## Dataset
The dataset contains Netflix content information, including:

- **Title** – Name of the content  
- **Category** – Movie or TV Show  
- **Director** – Director(s) of the content  
- **Cast** – Main cast  
- **Country** – Country of production  
- **Release Date** – When the content was added  
- **Rating** – Age rating of the content  
- **Duration** – Duration of the content  
- **Type** – Genre or content type  

> Dataset file: `Netflix Dataset.csv`

---

## Features
- **Content Trends Analysis:** Movies vs TV Shows over the years  
- **Top Genres:** Identify the most popular genres  
- **Country-wise Analysis:** Content distribution across countries  
- **Age Group Classification:** Kids, Teens, Adults, Unrated  
- **Monthly & Weekly Release Patterns**  
- **WordCloud of Top Cast Members**  
- **Correlation Analysis:** Duration vs Release Year  
- **Interactive Choropleth Map** for country-wise content  

---

## Data Cleaning & Feature Engineering
- Converted `Release_Date` to datetime and extracted `Year`, `Month`, `Day`, and `Weekday`  
- Filled missing values for `Director`, `Cast`, `Country`, and `Rating`  
- Extracted `Main_Genre` from the Type column  
- Cleaned `Duration` into numeric (`Duration_Num`) and type (`Duration_Type`)  
- Classified content into `Age_Group` based on `Rating`  

---

## Visualizations
All plots are saved in the `plots/` folder.  

### 1️⃣ Movies vs TV Shows Released per Year
![Movies vs TV Shows](plots/movies_vs_tvshows_per_year.png)

### 2️⃣ Top 10 Genres on Netflix
![Top Genres](plots/top_10_genres.png)

### 3️⃣ Stacked Bar – Movies vs TV Shows by Country (Top 10)
![Stacked Bar by Country](plots/movies_tvshows_by_country.png)

### 4️⃣ Interactive Choropleth – Netflix Content by Country
> Choropleth map saved as HTML: `plots/netflix_country_choropleth.html`  

### 5️⃣ Trends of Popular Genres Over Time
![Popular Genres Trend](plots/popular_genres_trend.png)

### 6️⃣ Content Release by Month
![Release by Month](plots/content_release_by_month.png)

### 7️⃣ Content Release by Day of Week
![Release by Day](plots/content_release_by_weekday.png)

### 8️⃣ WordCloud – Most Frequent Cast Members
![WordCloud](plots/wordcloud_top_cast.png)

### 9️⃣ Correlation Matrix – Duration vs Year
![Correlation Matrix](plots/correlation_matrix.png)

### 🔟 Distribution of Content by Age Group
![Age Group Distribution](plots/age_group_distribution.png)

---

## Installation & Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/SonuKumar7065/VOIS_AICTE_Oct2025_MajorProject_SonuKumar.git
2. Navigate to the project folder:
   ```bash
   cd VOIS_AICTE_Oct2025_MajorProject_SonuKumar
3. Install required Python libraries:
    ```bash
    pip install pandas numpy matplotlib seaborn plotly wordcloud
4. Run the analysis script (Colab/Jupyter Notebook):
   ```bash
   python Netflix_Data_Analysis.ipynb

## 📂 Folder Structure
- Content Available
    ```bash
    Netflix-Data-Analysis/
    │
    ├── Netflix_Data_Analysis.ipynb   # Main analysis script
    ├── Netflix Dataset.csv           # Dataset
    ├── plots/                        # Saved visualizations
    │   ├── movies_vs_tvshows_per_year.png
    │   ├── top_10_genres.png
    │   ├── movies_tvshows_by_country.png
    │   ├── popular_genres_trend.png
    │   ├── content_release_by_month.png
    │   ├── content_release_by_weekday.png
    │   ├── wordcloud_top_cast.png
    │   ├── correlation_matrix.png
    │   └── age_group_distribution.png
    ├── README.md                    # Project documentation

## 👨‍💻 Author  

**Sonu Kumar**  
VOIS for Tech Program on Conversational Data Analytics with LLMs

- GitHub: [SonuKumarAnalyst](https://github.com/SonuKumarAnalyst) 
- Contact: sonukumarsk5168@gmail.com

