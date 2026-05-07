# BANK MARKETING DASHBOARD Campaign 
Tableau HR dashboard analysing employee attrition, workforce trends, and key retention drivers.<br>
📊 Bank Marketing Campaign Dashboard — Built in Tableau<br>
🎯 Objective<br>
To evaluate the effectiveness of a bank’s marketing campaign by analysing customer characteristics, financial behaviour, and campaign strategies in order to improve conversion rates for term deposits.<br>
________________________________________
🧩 Dashboard Structure & Insights<br>
1️⃣ KPI Overview (Top-Left Panel)<br>
📌 Metrics:<br>
•	Conversion Rate: 47.38% <br>
•	Total Customers: 11,162 <br>
•	Average Balance: 1,529 <br>
•	Average Call Duration: 372 seconds <br>
💡 Insight:<br>
•	The campaign shows a moderate conversion rate, indicating strong opportunity for optimisation through better targeting and strategy refinement. <br>
________________________________________
2️⃣ Campaign Effectiveness — Contact Type (Top-Right Panel)<br>
📊 Visual:<br>
•	Bar chart comparing contact methods (cellular, telephone, unknown) <br>
💡 Insight:<br>
•	Cellular contact performs best, followed by telephone <br>
•	Unknown contact type has significantly lower effectiveness <br>
📌 Business Takeaway:<br>
•	Prioritise mobile-based outreach for higher engagement and conversions <br>
________________________________________
3️⃣ Customer Segmentation — Job vs Conversion (Middle-Right Panel)<br>
📊 Visual:<br>
•	Horizontal bar chart showing conversion rate by job role <br>
💡 Key Insights:<br>
•	Students and retirees show the highest conversion rates <br>
•	Management and unemployed segments also perform well <br>
•	Some roles underperform → opportunity for better targeting <br>
⚠️ Note:<br>
•	Values exceeding 100% indicate this is a relative index vs average, not raw conversion <br>
📌 Business Takeaway:<br>
•	Focus campaigns on high-performing professions <br>
•	Build segment-specific messaging <br>
________________________________________
4️⃣ Customer Segmentation — Education vs Conversion (Bottom-Right Panel)<br>
📊 Visual:<br>
•	Conversion rate across education levels <br>
💡 Insights:<br>
•	Tertiary education customers convert the most <br>
•	Secondary and unknown categories perform moderately <br>
•	Primary education group has the lowest conversion <br>
📌 Business Takeaway:<br>
•	Tailor messaging based on education level <br>
•	Use more sophisticated financial products for higher-educated segments <br>
________________________________________
5️⃣ Financial Behaviour — Loans vs Conversion (Left Panel)<br>
📊 Visual:<br>
•	Box plot showing conversion rate vs days since last contact <br>
💡 Insights:<br>
•	Some high-value outliers suggest timing alone is not enough <br>
•	Conversion is influenced by multiple interacting factors <br>
📌 Business Takeaway:<br>
•	Combine timing with customer profiling, not rely on recency alone <br>
________________________________________
🎯 Overall Business Insights<br>
✅ What drives conversion:<br>
•	Contact via cellular channels <br>
•	Longer, meaningful conversations <br>
•	Targeting students, retirees, and high-balance customers <br>
•	Customers with higher education levels <br>
Steps for the procedure: <br>
Step 1: Download the dataset from Kaggle. UCI Bank Data set<br>
Step 2: Open Tableau<br>
Step 3: Load the dataset and do data cleaning in the Data Source tab<br>
Step 4: Check the variables and set their types. For this analysis, all columns with digits are set as whole numbers, but the variable “Balance” is set as a decimal. <br>
Step 5: CREATE a calculated column for Valid Days Since Last Contact.<br>
Step 6: Check for Nulls & Remove with filters.<br>
Step 7: Create more calculated columns for variables like Subscribed Flag, Conversion rate, total customers etc. <br>
Step 8: Build Visualisations <br>
Step 9: Title: “Bank Marketing Campaign Analysis: Improving Deposit Conversion”<br>
✔ Add insight box:<br>
Examples:<br>
•	“Customers with higher balances show higher conversion rates” <br>
•	“Cellular contact outperforms telephone” <br>
•	“Previous campaign success strongly predicts future conversion”

