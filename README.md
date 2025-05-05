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

## Plot 3

Next, I’ll analyze how viewership varies based on release dates to identify any trends over time, such as seasonality or patterns around specific months:

<img width="975" alt="Screenshot 2025-04-29 at 5 10 12 PM" src="https://github.com/user-attachments/assets/eeed9cac-f473-4e4a-b5c0-02000ad0f889" />

The graph shows the total viewership hours by month, which reveals a notable increase in viewership during June and a sharp rise toward the end of the year in December. It suggests that Netflix experiences spikes in audience engagement during these periods, possibly due to strategic content releases, seasonal trends, or holidays, while the middle months have a steady but lower viewership pattern.

## Plot 4

To delve deeper, we can analyze the most successful content (both shows and movies) and understand the specific characteristics, such as genre or theme, that may have contributed to high viewership:

<img width="928" alt="Screenshot 2025-04-29 at 5 10 35 PM" src="https://github.com/user-attachments/assets/08ea8c27-524c-4ada-b9ec-392bcf83b1e7" />

The top 5 most-viewed titles on Netflix in 2023 are:

1.The Night Agent: Season 1 (English, Show) with 812.1 million hours viewed.

2. Ginny & Georgia: Season 2 (English, Show) with 665.1 million hours viewed.

3.King the Land: Limited Series (Korean, Movie) with 630.2 million hours viewed.

4.The Glory: Season 1 (Korean, Show) with 622.8 million hours viewed.

5.ONE PIECE: Season 1 (English, Show) with 541.9 million hours viewed.

English-language shows dominate the top viewership spots. But, Korean content also has a notable presence in the top titles, which indicates its global popularity.

## Plot 5

Now, let's have a look at the viewership tends by content type:

-> aggregate viewership hours by content type and release month  

<img width="1020" alt="Screenshot 2025-04-29 at 5 10 52 PM" src="https://github.com/user-attachments/assets/0af18239-4817-426a-81f5-c80b315a3817" />

The graph compares viewership trends between movies and shows throughout 2023. It shows that shows consistently have higher viewership than movies, peaking in December. Movies have more fluctuating viewership, with notable increases in June and October. This indicates that Netflix’s audience engages more with shows across the year, while movie viewership experiences occasional spikes, possibly linked to specific releases or events.

## Plot 6

Now, let's explore the total viewership hours distributed across differnt release season:

<img width="821" alt="Screenshot 2025-04-29 at 5 11 11 PM" src="https://github.com/user-attachments/assets/c34f1199-a051-4241-a95c-7b6abe9586e0" />

The graph indicates that viewership hours peak significantly in the Fall season, with over 80 billion hours viewed, while Winter, Spring, and Summer each have relatively stable and similar viewership around the 20 billion mark. This suggests that Netflix experiences the highest audience engagement during the Fall.

## Plot 7

Now let's analyze the number of content and their viewership hours acros months:

<img width="981" alt="Screenshot 2025-04-29 at 5 11 30 PM" src="https://github.com/user-attachments/assets/b1b178c4-7f44-470d-993e-b4a8e6dfb53b" />

While the number of releases is relatively steady throughout the year, viewership hours experience a sharp increase in June and a significant rise in December, despite a stable release count. This indicates that viewership is not solely dependent on the number of releases but influenced by the timing and appeal of specific content during these months.

## Plot 9

Next, let’s explore whether Netflix has a preference for releasing content on specific weekdays and how this influences viewership patterns:

<img width="1013" alt="Screenshot 2025-04-29 at 5 11 48 PM" src="https://github.com/user-attachments/assets/ec18984a-05b1-4b4b-a304-359008814e57" />

The graph highlights that most content releases occur on Fridays, with viewership hours also peaking significantly on that day. This suggests that Netflix strategically releases content toward the weekend to maximize audience engagement. The viewership drops sharply on Saturdays and Sundays, despite some releases, indicating that the audience tends to consume newly released content right at the start of the weekend, which makes Friday the most impactful day for both releases and viewership.

## Plot 10

To further understand the strategy, let’s explore specific high-impact dates, such as holidays or major events, and their correlation with content releases:

**Define significant holidays and events in 2023*

<img width="701" alt="Screenshot 2025-04-29 at 5 12 17 PM" src="https://github.com/user-attachments/assets/9c3831e0-27ab-478f-a4a9-804ac4fa0422" />

The data reveals that Netflix has strategically released content around key holidays and events. Some of the significant releases include:

**New Year’s Period**: The Glory: Season 1, La Reina del Sur: Season 3, and Kaleidoscope: Limited Series were released close to New Year’s Day, resulting in high viewership.

**Valentine’s Day**: Perfect Match: Season 1 and The Romantics: Limited Series were released on February 14th, which align with a romantic theme and capitalize on the holiday’s sentiment.


## 📌 Insights Gained

1. Shows dominate viewership hours compared to movies.
2. English content remains the most watched, with Korean content gaining strong traction.
3. Fall and December show significant spikes in viewership — hinting at strategic content drops.
4. The number of releases does not directly correlate with higher viewership — timing and type matter more.

## Summary

So, the content strategy of Netflix revolves around maximizing viewership through targeted release timing and content variety. Shows consistently outperform movies in viewership, with significant spikes in December and June, indicating strategic releases around these periods. The Fall season stands out as the peak time for audience engagement. Most content is released on Fridays, which aims to capture viewers right before the weekend, and viewership aligns strongly with this release pattern. While the number of releases is steady throughout the year, viewership varies, which suggests a focus on high-impact titles and optimal release timing over sheer volume.

📚 Future Improvements

* Include genre-specific analysis.
* Incorporate user ratings and completion rates for deeper insights.
* Predict future successful titles using machine learning.

## 👨‍💻 Author

-> Tanishq Sharma
Data Science and AI Developer @ FutureEx.ai
🔗 https://www.linkedin.com/feed/
📫 Email: tanishq1012l@yahoo.com
