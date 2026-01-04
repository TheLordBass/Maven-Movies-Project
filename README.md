# 🎬 DVD Rental Business Analysis

### 🚀 Executive Summary
**Goal:** Assess the health and value of a DVD rental business for a potential acquisition.
**Role:** Data Analyst.
**Tools:** SQL (MySQL/PostgreSQL), Data Interpretation.

---

## 📖 The Story
Imagine a group of investors wants to buy a DVD rental chain (similar to Blockbuster). Before they sign the deal, they need to perform **Due Diligence**. They handed me access to the company database and a list of critical questions about the inventory, staff, and customers.

My job was to use **SQL** to mine the raw data and provide clear, actionable answers to help them make a safe investment decision.

---

## 🔍 Key Questions & Insights
Here are the specific business problems I solved using SQL:

### 1. Who is running the stores? 
* **The Ask:** The investors want to meet the managers in person.
* **The Solution:** I joined 4 different tables (`Staff`, `Address`, `City`, `Country`) to create a complete contact list connecting every manager to their specific store location.

### 2. What are we actually buying? (Inventory Audit)
* **The Ask:** A full list of assets (films) and their value.
* **The Solution:** I generated a comprehensive inventory report detailing film ratings, rental rates, and replacement costs to help value the deal.

### 3. Where is the financial risk?
* **The Ask:** If certain movie categories stop renting, how much money do we lose?
* **The Solution:** I calculated the **Replacement Cost** per film category. This highlighted which genres (e.g., Action vs. Drama) carry the most financial risk if inventory is lost or damaged.

### 4. Who are the "Whales"? (Customer LTV)
* **The Ask:** We need to know who the best customers are.
* **The Solution:** I aggregated lifetime rentals and total payments to build a leaderboard of the top-spending customers, helping the marketing team target VIPs.

---

## 🛠️ Technical Skills Demonstrated
* **Complex Joins:** Combining data from 3+ tables to tell a complete story.
* **Aggregations:** Using `SUM`, `AVG`, and `COUNT` to summarize financial data.
* **Logic & Categorisation:** Using `CASE` statements to clean up data (e.g., grouping award types or flagging active/inactive users).
* **Data Cleaning:** Handling `NULL` values to ensure accurate reporting.

---

## 📊 Future Improvements
If I had more time, I would take this analysis further by:
* **Visualising the Data:** Connecting this database to **Tableau** or **PowerBI** to build a dashboard showing "Revenue by Store Location."
* **Churn Analysis:** identifying customers who haven't rented in 30+ days to launch a re-engagement campaign.

---

### 👋 About Me
I am a Data Analyst based in **Manchester, UK**, with a passion for uncovering insights in data. I specialise in **Excel, SQL, Tableau, and PowerBI**.

*Check out my code in the `.sql` file above!*
