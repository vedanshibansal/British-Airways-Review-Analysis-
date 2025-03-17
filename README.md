# ✈️ British Airways Customer Experience - Tableau Dashboard

### 📊 Analyzing 7.5+ Years of Customer Reviews (March 2016 - October 2023)

British Airways is a well-known airline, but **does it meet passenger expectations?**  
With real passenger ratings and feedback, we explored:

- **Which travel class gets the best ratings?** 💺  
- **How do customers rate seat comfort, food, and entertainment?** 🍽️📺  
- **Which aircraft models are rated the highest?** ✈️  
- **How do different countries rate their British Airways experience?** 🌍  
- **How do ratings change over time?** 📅  

To visualize these insights, we built an **interactive Tableau dashboard** that allows users to explore trends and passenger satisfaction metrics. Let’s dive in! 🚀  

https://public.tableau.com/views/BritishAirways_17421824344420/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
---

## 📂 Understanding the Data  

This project uses **two datasets** to analyze customer experience:  

### 1️⃣ Customer Reviews Dataset (`ba_reviews.xlsx`)
Contains real passenger feedback, including:  
- **Aircraft & Route** – Details of flights taken.  
- **Traveler Type** – Business, Leisure, Solo, or Family Travelers.  
- **Seat Type** – Economy, Business, First Class, or Premium Economy.  
- **Ratings (1-5 scale) for:**

   ![Ratings](https://github.com/vedanshibansal/British-Airways-Review-Analysis-/blob/23490dd5f437a96f663a2fc6c2d9bfa069fcd68e/Average%20Ratings "Average Ratings")
  
  - **Overall Rating** ⭐ (Avg: 4.19)  
  - **Seat Comfort** 🛋️ (Avg: 2.87)  
  - **Cabin Staff Service** 👩‍✈️ (Avg: 3.28)  
  - **Food & Beverages** 🍽️ (Avg: 2.38)  
  - **Ground Service** 🛄 (Avg: 3.03)  
  - **Value for Money** 💰 (Avg: 2.78)  
  - **Entertainment** 🎬 (Avg: 1.44)  

### 2️⃣ Country Mapping Dataset (`Countries.xlsx`)
- Links **flight routes to continents & regions**.
- Used to **map customer ratings by country**.

---

## 🛠 Data Processing & Preparation  

To make the data **ready for visualization in Tableau**, we:  
✔ **Cleaned Data** – Removed incomplete ratings & fixed inconsistencies.  
✔ **Calculated Metrics** – Found **average ratings by month, country, and aircraft type**.  
✔ **Mapped Data** – Connected reviews to geographic locations for **better visualization**.  

---

## 📈 Key Insights from the Data  

### 1️⃣ Which travel class gets the best ratings? 💺  
📌 _Insert Screenshot of Class Ratings Comparison_

- **First Class (4.39/5)** and **Economy (4.36/5)** are the highest-rated.  
- **Business Class (3.93/5)** ranks lower on **value for money**.  
- **Premium Economy (4.22/5)** sits between Business and Economy in overall satisfaction.  

### 2️⃣ What are the strongest & weakest parts of British Airways service? 📊  


- **Best-rated category:** Cabin Crew Service (**3.28/5**) 🏆  
- **Worst-rated category:** Entertainment (**1.44/5**) ❌  
- **Food & Beverages (2.38/5)** remains a consistent **area of dissatisfaction**.  

### 3️⃣ Which aircraft models are rated the highest? ✈️  
📌 _Insert Screenshot of Aircraft Comfort Scores_

- **Top-rated aircraft:** Airbus A350, Boeing 787 Dreamliner, and Embraer E-190.  
- **Lowest-rated aircraft:** Older Boeing 747s, A319s, and certain A320 variants.  
- **Bigger aircraft (A380 & B777)** score higher on comfort but aren't necessarily the best-rated overall.  

### 4️⃣ How do different countries rate British Airways? 🌍  
📌 _Insert Screenshot of Global Ratings Heatmap_

- **Best-rated flights:** Czechia (9.5/10), Taiwan, and Turkey.  
- **Worst-rated flights:** Australia (4.18/10), Belgium (2.4/10) – mostly due to **seat comfort and food complaints**.  
- **Flights to Asia** tend to receive **better ratings** than flights within Europe or to the US.  

### 5️⃣ How do ratings change over time? 📅  
📌 _Insert Screenshot of Monthly Ratings Trend_

- **March & September** consistently have **higher ratings**.  
- **December-January** sees lower ratings, likely due to **holiday travel congestion and delays**.  
- **No long-term trend** of improvement—ratings fluctuate based on the season.  

---

## 📊 Final Dashboard – Bringing It All Together  

📌 _Insert Screenshot of Full Tableau Dashboard_  

This **interactive Tableau dashboard** allows users to:  
✅ **Filter by seat type, traveler type, aircraft model, and country.**  
✅ **Analyze British Airways service quality across different metrics.**  
✅ **Track customer satisfaction trends over time.**  
✅ **Compare experience ratings for different flight routes.**  

---

## 📂 Files Included in This Project  

📁 **BritishAirways.twbx** – The **interactive Tableau dashboard**.  
📁 **ba_reviews.xlsx** – The **raw customer ratings dataset**.  
📁 **Countries.xlsx** – **Geographic mapping dataset**.  
📁 **visualizations/** – **Screenshots of key dashboard insights**.  

---

## 🔧 How to Use This Dashboard  

1️⃣ Open **BritishAirways.twbx** in **Tableau Desktop**.  
2️⃣ Explore **filters & interactive charts** to analyze passenger feedback.  
3️⃣ Gain insights into **travel experience, service quality & satisfaction trends**.  

---

## 🚀 Future Enhancements  

📌 **Add real-time customer review tracking**.  
📌 **Include sentiment analysis for better complaint detection**.  
📌 **Compare British Airways with competitors** for industry-wide benchmarking.  

---

## 🎯 Contribute & Explore  

This project turns real passenger ratings into insights using **Tableau**.  
Want to contribute? **Fork the repo** & share your analysis! 🚀  

📌 **GitHub Repo:** [Your GitHub Link Here]  

---

👨‍💻 **Author:** [Your Name]  
📧 **Contact:** [Your Email]  

🌟 **If you found this project useful, consider starring ⭐ the repository!**  

