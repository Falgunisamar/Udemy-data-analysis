## 📜 Project Overview

This project is an **Exploratory Data Analysis (EDA)** of a dataset containing information on Udemy courses. The primary goal is to uncover **trends, patterns, and insights** related to course prices, popularity, content, and duration.

The analysis seeks to answer key business questions such as:

* What are the different subjects for which Udemy offers courses?
* Which subject has the maximum number of courses?
* What are the top-selling courses?
* What are the least-selling courses?
* What is the maximum number of subscribers for each course level?

---

### 📂 Dataset

* **Source**: Udemy Courses Dataset (sourced from Kaggle)
* **File**: `udemy_courses.csv`
* **Columns**:

  * `course_id` → Unique course identifier
  * `course_title` → Name of the course
  * `is_paid` → Free or paid status
  * `price` → Course price
  * `num_subscribers` → Number of enrolled students
  * `num_reviews` → Number of reviews submitted
  * `num_lectures` → Total lectures in the course
  * `level` → Course level (Beginner, Intermediate, Expert)
  * `content_duration` → Duration of course content
  * `published_timestamp` → Publication date
  * `subject` → Course category

---

### 🛠️ Methodology

The analysis was carried out in **Jupyter Notebook** using Python. Key steps include:

1. **Data Loading & Cleaning** → Handling missing values, duplicates, and data formatting.
2. **Exploratory Data Analysis (EDA)** → Statistical summaries and visual exploration.
3. **Data Visualization** → Charts and graphs using **Matplotlib** and **Seaborn**.
4. **Insight Generation** → Answering business questions and highlighting key findings.

---

### 📊 Results & Key Findings

The analysis reveals:

* **Price vs Popularity** → Free courses tend to attract more subscribers, but paid courses often show better engagement.
* **Subject Trends** → Certain subjects dominate the platform with a higher number of courses.
* **Course Level Insights** → Beginner-level courses have the highest number of subscribers.
* **Content Duration vs Subscribers** → Course length (lectures & duration) shows a moderate correlation with popularity.
* **Reviews & Subscribers** → Strong correlation between reviews and total subscribers.
  
<img width="808" height="469" alt="image" src="https://github.com/user-attachments/assets/b7a7daf5-69a5-4047-ada2-5764dc7a9e83" />


of subscribers.
