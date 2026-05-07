# Bank-Data-_-UCI
Tableau HR dashboard analysing employee attrition, workforce trends, and key retention drivers.
📊 Bank Marketing Campaign Dashboard — Built in Tableau
🎯 Objective
To evaluate the effectiveness of a bank’s marketing campaign by analysing customer characteristics, financial behaviour, and campaign strategies in order to improve conversion rates for term deposits.
________________________________________
🧩 Dashboard Structure & Insights
1️⃣ KPI Overview (Top-Left Panel)
📌 Metrics:
•	Conversion Rate: 47.38% 
•	Total Customers: 11,162 
•	Average Balance: 1,529 
•	Average Call Duration: 372 seconds 
💡 Insight:
•	The campaign shows a moderate conversion rate, indicating strong opportunity for optimisation through better targeting and strategy refinement. 
________________________________________
2️⃣ Campaign Effectiveness — Contact Type (Top-Right Panel)
📊 Visual:
•	Bar chart comparing contact methods (cellular, telephone, unknown) 
💡 Insight:
•	Cellular contact performs best, followed by telephone 
•	Unknown contact type has significantly lower effectiveness 
📌 Business Takeaway:
•	Prioritise mobile-based outreach for higher engagement and conversions 
________________________________________
3️⃣ Customer Segmentation — Job vs Conversion (Middle-Right Panel)
📊 Visual:
•	Horizontal bar chart showing conversion rate by job role 
💡 Key Insights:
•	Students and retirees show the highest conversion rates 
•	Management and unemployed segments also perform well 
•	Some roles underperform → opportunity for better targeting 
⚠️ Note:
•	Values exceeding 100% indicate this is a relative index vs average, not raw conversion 
📌 Business Takeaway:
•	Focus campaigns on high-performing professions 
•	Build segment-specific messaging 
________________________________________
4️⃣ Customer Segmentation — Education vs Conversion (Bottom-Right Panel)
📊 Visual:
•	Conversion rate across education levels 
💡 Insights:
•	Tertiary education customers convert the most 
•	Secondary and unknown categories perform moderately 
•	Primary education group has the lowest conversion 
📌 Business Takeaway:
•	Tailor messaging based on education level 
•	Use more sophisticated financial products for higher-educated segments 
________________________________________
5️⃣ Financial Behaviour — Loans vs Conversion (Left Panel)
📊 Visual:
•	Box plot showing conversion rate vs days since last contact 
💡 Insights:
•	Wide spread indicates inconsistent impact of recency 
•	Some high-value outliers suggest timing alone is not enough 
•	Conversion is influenced by multiple interacting factors 
📌 Business Takeaway:
•	Combine timing with customer profiling, not rely on recency alone 
________________________________________
🎯 Overall Business Insights
✅ What drives conversion:
•	Contact via cellular channels 
•	Longer, meaningful conversations 
•	Targeting students, retirees, and high-balance customers 
•	Customers with higher education levels 
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

