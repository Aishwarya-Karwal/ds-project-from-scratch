# Job Role Classification & Salary Trends Analysis

## Project Overview
This project focuses on analyzing job market data scraped from **Glassdoor** to gain insights into salary trends and job classifications. Due to inconsistencies in salary values, the project shifts from direct salary prediction to **job role classification**, leveraging clustering and supervised learning techniques. **Pandas and Numpy** were used for efficient data processing, filtering, and structuring before applying machine learning models.

## Tech Stack
- **Python** (Pandas, NumPy, Scikit-learn, Selenium)
- **Machine Learning** (Regression, Clustering, Classification)
- **Data Visualization** (Matplotlib, Seaborn)

## Workflow
1. **Data Collection:**
   - Scraped job postings using **Selenium**.
   - Collected details like **company, location, job title, job description, rating, salary estimates, industry, and required skills**.
   
2. **Data Cleaning & Preprocessing:**
   - Handled missing values and removed redundant data.
   - Used **Python Pandas** for data filtering, aggregation, and restructuring.
   - Performed **feature engineering** (dummy variables, frequency encoding, bag-of-words, one-hot encoding, custom feature creation).
   
3. **Exploratory Data Analysis (EDA):**
   - Analyzed trends in **salary ranges, job descriptions, skill distributions, and industry insights**.
   - Utilized **summary statistics** for deeper data exploration .
   - Visualized key patterns using **Seaborn & Matplotlib**.
   
4. **Clustering & Classification Approach:**
   - Applied **clustering algorithms (Hierarchical Clustering)** to group job roles based on skills and job descriptions.
   - Used clustering results as a basis for a **classification model** to predict job categories.
   - Trained and evaluated **Random Forest, Decision Trees, and Logistic Regression** models.
   
5. **Results & Insights:**
   - Identified **job role segments** and their key characteristics.
   - Identified the data lacked a direct relationship of any of the feature columns with salary, can be because of the dynamic market and data scraped.
   - Provided insights into **salary trends and in-demand skills**.
   - Enabled **job classification predictions**, improving understanding of industry patterns.


## Future Improvements
- Enhance **data collection** by scraping more job listings for better insights.
- Explore **deep learning models** for improved classification performance.
- Integrate **real-time salary prediction APIs** for dynamic insights.
`

## Credits
- **Data Source:** Glassdoor (Scraped via Selenium), 
- **Developed By:** Aishwarya Karwal

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
