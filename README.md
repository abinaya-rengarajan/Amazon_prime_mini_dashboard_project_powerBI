# Amazon Prime Mini Power BI Dashboard

## 🌟 Overview

This repository contains a **mini Power BI dashboard** created using a **subset of the Amazon Prime Video dataset**.  
- Original dataset source: [Kaggle – Amazon Prime Movies and Shows](https://www.kaggle.com/datasets/prasertk/amazon-prime-movies-and-shows)  
- Dataset used: **200 rows** (derived from the original dataset for demonstration purposes)  

The dashboard provides **interactive visual storytelling** about Amazon Prime Video content, including:  
- Total content metrics  
- Age ratings distribution  
- Genre trends  
- Global content distribution  
- Format comparison (Movies vs TV Shows)  
- Release patterns over the years  

The layout is designed in **three rows** for clear and intuitive storytelling: **Top Metrics → Content Insights → Global & Format Trends**.

---

## 🏆 Dashboard Structure

### **1️⃣ Row 1 – Top Metrics at a Glance**

The **first row** contains **six cards** summarizing key information about the dataset:

| Card            | Value               | Description                                            |
| --------------- | ------------------ | ------------------------------------------------------ |
| Total Titles    | 199                | ➤ Total number of shows and movies in the mini dataset |
| Total Ratings   | 17                 | ➤ Count of distinct content ratings (PG, 13+, R, etc.) |
| Total Genres    | 80                 | ➤ Number of unique genres (`Listed In` column)         |
| Total Directors | 107                | ➤ Count of unique directors                             |
| Earliest Date Added | 30 March        | ➤ Shows when content was first added                  |
| Latest Date Added   | 32 [or latest date] | ➤ Shows when the most recent content was added       |

**Functionality:**  
- Provides **quick overview** of dataset size, diversity, and temporal range  
- Values **update dynamically** if dataset changes  

---

### **2️⃣ Row 2 – Content Insights**

The **middle row** focuses on **content composition and popularity** and contains **three visuals**:

1. **Shows by Rating (Clustered Column Chart)**  
   - ➤ X-axis: Rating categories (PG, 13+, R, etc.)  
   - ➤ Y-axis: Count of shows (`Title`)  
   - ➤ Title: “Shows by Rating”  
   - **Purpose:** Visualizes distribution of shows across age ratings  

2. **Amazon Prime Logo with Watermark**  
   - ➤ Centered between the two charts for branding  
   - ➤ Watermark text: `"Insights by Abinaya Rengarajan"`  
   - **Purpose:** Enhances dashboard aesthetics and personalization  

3. **Total Shows by Genre (Clustered Bar Chart)**  
   - ➤ Y-axis: Genre (`Listed In`)  
   - ➤ X-axis: Count of shows (`Title`)  
   - ➤ Title: “Total Shows by Genre”  
   - **Features:** Scrollbar enabled to accommodate all genres  
   - **Purpose:** Displays popularity and distribution of genres  

> This row **bridges top metrics with deeper insights**, combining visual storytelling and branding.

---

### **3️⃣ Row 3 – Global & Format Trends**

The **bottom row** shows **geographic distribution and format comparisons** with three visuals:

1. **Total Shows by Country (Filled Map)**  
   - ➤ Location: Country  
   - ➤ Values: Count of shows (`Title`)  
   - ➤ Legend: Type (`Movie` vs `TV Show`)  
   - ➤ Title: “Total Shows by Country”  
   - **Purpose:** Provides a global overview of content availability  

2. **Movies vs TV Shows (Donut Chart)**  
   - ➤ Legend: Type (`Movie` vs `TV Show`)  
   - ➤ Values: Count of shows (`Title`)  
   - ➤ Title: “Format Comparison: Movies vs TV Shows”  
   - **Purpose:** Shows proportion of Movies vs TV Shows  

3. **Shows by Release Year (Line Chart)**  
   - ➤ X-axis: Release Year  
   - ➤ Y-axis: Count of shows (`Title`)  
   - ➤ Legend: Type (`Movie` vs `TV Show`)  
   - ➤ Title: “Shows by Release Year”  
   - **Purpose:** Displays content growth over the years for each type  

> This row **rounds out the dashboard**, providing insights into global distribution, format, and temporal trends.

---

## 📂 Files in Repository

- `Amazon_Prime_Mini_dataset.csv` → Derived mini dataset (200 rows)  
- `AmazonPrimeMiniDashboard.pbix` → Power BI file with all visuals, formatting, and interactivity  
- `Dashboard_Screenshot.png` → Static screenshot of the completed dashboard  

---

## 🛠 How It Was Created

1. **Dataset Preparation**  
   - Downloaded the full dataset from Kaggle  
   - Extracted **200 rows** for a lightweight, illustrative dashboard  

2. **Visualizations**  
   - **Top Row:** Cards showing total titles, ratings, genres, directors, start and end dates  
   - **Middle Row:** Shows by rating (clustered column), Amazon Prime logo with watermark, shows by genre (clustered bar)  
   - **Bottom Row:** Filled map (shows by country), donut chart (movies vs TV shows), line chart (shows by release year)  

3. **Branding & Personalization**  
   - Logo placed at the center of middle row  
   - Watermark text: `"Insights by Abinaya Rengarajan"`  

4. **Interactivity**  
   - Scrollbars for long lists (genres)  
   - Hover tooltips for maps and charts  
   - Dynamic counts and visuals update automatically with the dataset  

---

## ⚡ How to Use

1. Download `Amazon_Prime_Mini_dataset.csv`  
2. Open `AmazonPrimeMiniDashboard.pbix` in **Power BI Desktop**  
3. Interact with the dashboard: hover over charts, scroll through genres, and explore data by country, rating, or release year  
4. Optional: Replace dataset with a larger version, and visuals will update automatically  

---

## 📝 Notes

- Lightweight dashboard with **200 rows**, fast and responsive  
- Fully functional **offline**, no Power BI Service login required  
- Clear **storytelling flow**:  
  - **Top metrics** → **Content insights** → **Global & format trends**  
- Branding includes **Amazon Prime logo** and **personal watermark**  
- Ideal for demonstrating **Power BI visualization skills and data storytelling**

---

