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

![Dashboard ](https://github.com/vedanshibansal/British-Airways-Review-Analysis-/blob/3768bf16c481d7eb3330c4b5050e930253a51532/Dashboard%201%20(2).png)

[Visit British Airways Tableau  Dashboard](https://public.tableau.com/views/BritishAirways_17421824344420/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

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

![Filters](https://github.com/vedanshibansal/British-Airways-Review-Analysis-/blob/3768bf16c481d7eb3330c4b5050e930253a51532/Filters "Filters")
![Filters](https://github.com/vedanshibansal/British-Airways-Review-Analysis-/blob/3768bf16c481d7eb3330c4b5050e930253a51532/Filters%202 "Filters")

✔ **Mapped Data** – Connected reviews to geographic locations for **better visualization**.  

---

## 📈 Key Insights from the Data  

### 1️⃣ How does British Airways perform across different service categories? 💺🍽️🎬  
![Service Categories](https://github.com/vedanshibansal/British-Airways-Review-Analysis-/blob/3768bf16c481d7eb3330c4b5050e930253a51532/Average%20Ratings)  

- **Best-rated category:** Cabin Staff Service (**Avg: 3.28/5**) 🏆  
- **Worst-rated category:** Entertainment (**Avg: 1.44/5**) ❌  
- **Food & Beverages** receive consistently **low ratings (Avg: 2.38/5)**, showing **room for improvement**.  

### 2️⃣ Which aircraft models receive the best and worst ratings? ✈️  
![Aircraft Ratings](https://github.com/vedanshibansal/British-Airways-Review-Analysis-/blob/3768bf16c481d7eb3330c4b5050e930253a51532/Aircraft%20Ratings)  
- **Highest-rated aircraft:** Boeing 747-400 (**4.7/5**) and Boeing 787 (**4.4/5**).  
- **Lowest-rated aircraft:** A321 and Boeing 777-200, which score **below 4.0/5**.  
- **Newer aircraft generally perform better** than older models in comfort and overall rating.  

### 3️⃣ How do different countries rate their British Airways experience? 🌍  
![Country Ratings](https://github.com/vedanshibansal/British-Airways-Review-Analysis-/blob/3768bf16c481d7eb3330c4b5050e930253a51532/Country%20Ratings)  

- **Best-rated flights:** Routes to **Czechia, Taiwan, and Turkey** show the highest satisfaction.  
- **Lowest-rated flights:** Passengers flying to **Australia and Belgium** report **lower satisfaction**, especially with **food and seat comfort**.  
- **Flights to Asia** generally receive **better ratings** than flights within Europe or to the US.  

### 4️⃣ How do ratings change over time? 📅  
![Monthly Ratings Trend](https://github.com/vedanshibansal/British-Airways-Review-Analysis-/blob/3768bf16c481d7eb3330c4b5050e930253a51532/Month-wise%20Ratings)  

- **Ratings fluctuate significantly over time**, with notable **peaks and drops**.  
- **March & September** consistently have the **best ratings**.  
- **December-January** tends to have **lower ratings**, likely due to **holiday travel congestion and delays**.  

---

## 📊 Final Dashboard – Bringing It All Together  
![Dashboard with filters Applied](https://github.com/vedanshibansal/British-Airways-Review-Analysis-/blob/3768bf16c481d7eb3330c4b5050e930253a51532/Dashboard%201%20(3).png) 
  

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

🌟 **If you found this project useful, consider starring ⭐ the repository!**  

