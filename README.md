# Interactive Movie Revenue Dashboard (R Shiny)

## 📌 Project Overview
This project builds an **interactive dashboard** using **R Shiny** to analyze and visualize movie revenue data (worldwide, domestic, and international).  
Data was collected through **web scraping** from [The Numbers](https://www.the-numbers.com/movie/budgets/all), then preprocessed, analyzed, and visualized to gain insights into global box office performance.

## 🚀 Features
- **Web scraping** of real-world movie revenue data  
- **Data preprocessing**: cleaning, transformation, reduction  
- **Descriptive statistics**: mean, median, variance, quartiles, percentiles  
- **Interactive visualizations**: scatter plots, bar charts, density plots, pie charts  
- **R Shiny dashboard** with:
  - Table filtering & searching  
  - Statistical summaries  
  - Customizable graph selection  

## 🛠️ Tools & Libraries
- **R**  
- **R Shiny** – interactive dashboard  
- **rvest** – web scraping  
- **dplyr** – data manipulation  
- **ggplot2**, **ggpie** – visualization  

## 📊 Data Source
Movie revenue data scraped from [The Numbers](https://www.the-numbers.com/movie/budgets/all), including:  
- Movie title  
- Release year  
- Worldwide box office revenue  
- Domestic box office revenue  
- International box office revenue  

## ⚡ How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/movie-revenue-dashboard.git
   ```
2. Open `app.R` in **RStudio**  
3. Install required libraries if not already installed:
   ```R
   install.packages(c("shiny", "rvest", "dplyr", "ggplot2", "ggpie", "DT"))
   ```
4. Run the Shiny app:
   ```R
   shiny::runApp("app.R")
   ```

## 📚 Learning Outcomes
- Practical experience in **web scraping** and handling real-world noisy data  
- Applied **data preprocessing and descriptive statistics**  
- Built a **fully interactive R Shiny dashboard** for data exploration  
