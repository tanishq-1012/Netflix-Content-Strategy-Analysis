# Netflix-Content-Strategy-Analysis

This project explores and analyzes the content strategy of **Netflix** using Python and data visualization tools. By evaluating how shows and movies performed in 2023 in terms of viewership hours, release patterns, language distribution, and more, the analysis aims to uncover insights into Netflix’s content planning and audience engagement trends.
Content Strategy Analysis means analyzing how content is created, released, distributed, and consumed to achive specific goals, such as maximizing audience engagement, viewership, brand, reach or revenue.

## 🔍 Objective

To understand **how Netflix creates, releases, and distributes** its content and how viewers **consume** that content — helping us evaluate what kind of content, language, timing, and formats contribute to successful performance.

## 📁 Dataset

The dataset contains information about all the Netflix content released in **2023**, including:

- Title
- Content Type (Show or Movie)
- Language Indicator
- Release Date
- Hours Viewed (in millions)
- Availability Status

For the task of netflix content strategy analysis, we need data based on content titles, types (shows, movie), genre, language, and release details (date, day of the week, season) to understand timing and content performance. Viewership metrics like hours viewed are also crucial for measuring audience engagement.

## 🛠️ Technologies Used

- **Python**
- **Pandas** for data cleaning and preprocessing
- **Plotly** for interactive and visually appealing graphs

## 📊 Key Analyses Performed

1. **Data Cleaning:**
   - Converted viewership hours to numeric format for analysis.

2. **Content Type Analysis:**
   - Compared total viewership hours between shows and movies.

3. **Language-wise Viewership:**
   - Analyzed which languages performed best in terms of watch hours.

4. **Monthly Trends:**
   - Investigated how content released in different months performed.

5. **Top Performing Titles:**
   - Identified the top 5 most-watched shows/movies in 2023.

6. **Seasonal Trends:**
   - Compared viewership by seasons: Winter, Spring, Summer, Fall.

7. **Release Volume vs Engagement:**
   - Analyzed the number of monthly releases vs total viewership hours.

## 📈 Visualizations Included

- Bar charts of viewership by content type and language
- Line graphs of monthly trends for shows and movies
- Seasonal bar plots showing viewership distribution
- Dual-axis plots to compare number of releases and viewership

All visualizations are created using `Plotly` with a clean and interactive design.

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/netflix-content-strategy-analysis.git
   cd netflix-content-strategy-analysis

## Dependencies

pip install pandas plotly

## Run the analysis notebook or Python script:

python netflix_analysis.py
or open the notebook in Jupyter/Colab

Make sure to place the dataset file (netflix_content_2023.csv) in the project directory.

## 📁 Dataset

Now lets started with the task of Netflix Comtent Strategy Analysis by importing the necessary Python libraries and the dataset,

<img width="976" alt="Screenshot 2025-04-29 at 5 07 09 PM" src="https://github.com/user-attachments/assets/e307cc3f-51f9-420c-a20f-4a0221300138" />

______________________________________________________________________________

Lets start with cleaning and processing the 'Hours Viewed' column to prepare it for analysis

<img width="915" alt="Screenshot 2025-04-29 at 5 07 39 PM" src="https://github.com/user-attachments/assets/dd171cae-0483-4ccc-9a72-86c7f9e0f5eb" />

------------------------------------------------------------------------------

The “Hours Viewed” column has been successfully cleaned and converted to a numeric format. Now, I’ll analyze trends in content type to determine whether shows or movies dominate viewership. Let’s visualize the distribution of total viewership hours between Shows and Movies:

<img width="531" alt="Screenshot 2025-04-29 at 5 07 59 PM" src="https://github.com/user-attachments/assets/46bb7fc5-4acb-4bbf-ab86-b9567b919fd0" />

## Plot 1

<img width="748" alt="Screenshot 2025-04-29 at 5 08 19 PM" src="https://github.com/user-attachments/assets/cec5ef98-fa80-4afe-ad47-d7794072b976" />

The visualization indicates that shows dominate the total viewership hours on Netflix in 2023 compared to movies. This suggests that Netflix’s content strategy leans heavily toward shows, as they tend to attract more watch hours overall.

## Plot 2

Next, let’s analyze the distribution of viewership across different languages to understand which languages are contributing the most to Netflix’s content consumption:

<img width="975" alt="Screenshot 2025-04-29 at 5 09 51 PM" src="https://github.com/user-attachments/assets/9b9c1ca8-4163-4bf8-b372-54deef8d835e" />

The visualization reveals that English-language content significantly dominates Netflix’s viewership, followed by other languages like Korean. It indicates that Netflix’s primary audience is consuming English content, although non-English shows and movies also have a considerable viewership share, which shows a diverse content strategy.

