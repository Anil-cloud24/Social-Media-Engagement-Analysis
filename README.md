# 📊 Social Media Post Engagement Analysis (Pandas & NumPy Project)

## Project Overview
This project performs **data analysis on social media posts** to extract meaningful insights about post performance and user engagement. The dataset contains posts with attributes like **Likes, Shares, Comments, User IDs, Content Types, and Post IDs**.

The project is limited to **NumPy and Pandas only** (No ML libraries), focusing on **Data Aggregation, Grouping, Ranking, Outlier Detection, and Engagement Metrics**.

---

## Dataset
A CSV file containing social media posts data with the following columns:
- `PostID`
- `UserID`
- `ContentType` (e.g., Image, Video, Text)
- `Likes`
- `Shares`
- `Comments`
- `PostDate` (optional for advanced temporal tasks)

---

## Tasks Performed
### **Task 1: Basic Aggregations**
- Total number of posts.
- Total Likes, Shares, and Comments across all posts.
- Average Likes, Shares, Comments per post.

### **Task 2: Content-Type Based Analysis**
- Aggregated Likes, Shares, and Comments for each Content Type.
- Identified Content Type with the highest average engagement per post.

### **Task 3: User Engagement Analysis**
- Found Top 3 Users with the highest cumulative engagement.
- Calculated average engagement per post for each user.
- Computed Global Average Engagement per Post per User.

### **Task 4: Temporal Trends (Optional if PostDate exists)**
- Analyze posting frequency over time.
- Engagement trend analysis (daily/weekly/monthly).

### **Task 5: Ratio Analysis & Outlier Detection**
- Calculated Like-to-Comment and Share-to-Like Ratios per post.
- Standardized ratios using Z-Score method.
- Flagged posts with unusually high/low ratios.

### **Task 6: Engagement Scoring & Post Ranking**
- Created a custom Engagement Score:
- Engagement Score = (Likes * 0.5) + (Comments * 2) + (Shares * 3)
- Ranked posts based on this score.
- Listed Top 5 posts with the highest Engagement Metrics.

---

## Requirements
- Python 3.x
- Pandas
- NumPy
- Matplotlib (Optional for visualizations)

---

## How to Run
1. Clone this repository or download the `.ipynb` or `.py` file.
2. Place the dataset CSV file in the project directory.
3. Run the script using Jupyter Notebook or Python IDE.
4. Follow the step-wise tasks to see the outputs.

---

## Example Insights:
- ContentType 'Video' has the highest average likes per post.
- UserID 'U12345' is the top engager with over 10,000 cumulative interactions.
- Posts with high Like-to-Comment Ratios are mostly Text posts.
- Top 5 engaging posts are dominated by Share-heavy content.

---

## Folder Structure
```text
/project
│
├── data/
│ └── social_media_posts.csv
│
├── analysis/
│ └── social_media_analysis.ipynb
│
└── README.md
```
---

## Author
- **Anil Venkat Venkatachalam**

---

## License
This project is for educational and practice purposes. Free to use and modify.


