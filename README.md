# 👋 Hi, I'm Lalit Sharma

## 💡 About Me

I build things with data. Right now that means migrating 10 years of messy operational records into a clean cloud database at Broswave Technologies, and building Power BI dashboards that replaced hours of manual work.

That's the professional version. The real story is that I got hooked on data because I wanted to know why two houses on the same street can sell for wildly different prices. So I scraped thousands of Redfin listings and built a model that predicts housing prices with around 95% accuracy. Then I got curious about crime and property values, so I dug through 61K records across Boston. Now I'm pulling apart GPU benchmark data and AI upscaling claims to figure out if the generational price jumps are backed by real performance improvements or if companies are just slapping "AI-powered" on everything to justify charging more. Each question leads to the next one (follow along with the [GPU project](https://github.com/Lalitsh03/gpu-upscaling-project), that one's still in progress).

I am based in San Diego with a master's in MIS from Cal State Fullerton. I work primarily with SQL, Python, and Power BI, and I care more about whether the insight is useful than whether the model is fancy.

🏐 Outside of work, I play volleyball and dream of opening a **Himalayan-themed café** someday, blending my cultural roots with a modern coffee-house vibe.
🎮 I'm a hardware nerd at heart. I follow CPU/GPU launches way too closely, geek out over new advancements like UE5's Nanite and Lumen and how they push rendering boundaries, and I'm always reading up on what's next in gaming tech. When I'm not analyzing benchmarks for my GPU project, you'll find me grinding CS2, creating community maps, and getting outplayed by 12-year-olds with better reflexes. Hoping to land a project someday where I can bring the data side and the hardware side together.

## 🛠 Tech Stack

### 💻 Programming & Data
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)](#)
[![R](https://img.shields.io/badge/R-276DC3?logo=r&logoColor=fff)](#)
[![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=fff)](#)
[![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=fff)](#)
[![NumPy](https://img.shields.io/badge/NumPy-4DABCF?logo=numpy&logoColor=fff)](#)
[![Scikit-learn](https://img.shields.io/badge/-scikit--learn-%23F7931E?logo=scikit-learn&logoColor=fff)](#)
[![Matplotlib](https://custom-icon-badges.demolab.com/badge/Matplotlib-71D291?logo=matplotlib&logoColor=fff)](#)
[![ETL](https://custom-icon-badges.demolab.com/badge/ETL-9370DB?logo=etl-logo&logoColor=fff)](#)

### 📊 Visualization & BI
[![Power BI](https://custom-icon-badges.demolab.com/badge/Power%20BI-F1C912?logo=power-bi&logoColor=fff)](#)
[![Tableau](https://custom-icon-badges.demolab.com/badge/Tableau-0176D3?logo=tableau&logoColor=fff)](#)
[![Excel](https://img.shields.io/badge/Excel-217346?logo=microsoft-excel&logoColor=fff)](#)
[![Looker Studio](https://img.shields.io/badge/Looker_Studio-4285F4?logo=googleanalytics&logoColor=fff)](#)

### ⚙ Tools & Systems
[![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=fff)](#)
[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=fff)](#)
[![Microsoft Fabric](https://img.shields.io/badge/Microsoft%20Fabric-0078D4?logo=microsoft&logoColor=fff)](#)
[![JIRA](https://img.shields.io/badge/JIRA-0052CC?logo=jira&logoColor=fff)](#)
[![REST API](https://img.shields.io/badge/REST_API-0096D6?logo=rest-api&logoColor=fff)](#)
[![GCP](https://img.shields.io/badge/GCP-4285F4?logo=googlecloud&logoColor=fff)](#)
[![Alteryx](https://img.shields.io/badge/Alteryx-0078C0?logo=alteryx&logoColor=fff)](#)

## 🔥 Currently Working On

### 🖥️ [GPU Upscaling & AI Pricing Analysis](https://github.com/Lalitsh03/gpu-upscaling-project)
*🔄 In Progress*

Investigating whether the steep price increases in AI/GPU hardware are justified by actual generational performance gains, or if manufacturers are using AI upscaling and the "AI" label to mask marginal improvements and inflate margins. Comparing price-to-performance ratios across GPU generations and analyzing whether AI-powered upscaling (DLSS, FSR, XeSS) is genuine innovation or a workaround for underwhelming native performance.

`Python` `Pandas` `Web Scraping` `Data Visualization` `Statistical Analysis`

**⭐ Star the repo to follow along as this one develops.**

## 💼 Experience

### Broswave Technologies Private Limited | Data Analyst (Contract)
*Jan 2026 - Present · San Diego, CA*

🔹 Migrating and validating **10+ years of legacy operational data** into a centralized cloud database, ensuring data integrity and governance across business functions  
🔹 Building **Power BI dashboards** using DAX and data modeling, reducing manual data retrieval time by **~50%**  
🔹 Writing advanced SQL (CTEs, joins, window functions) to clean and structure historical data  
🔹 Training staff on standardized data entry and reporting workflows

### Saayam For All | Business Analyst
*Mar 2025 - Jan 2026 · San Jose, CA*

🔹 Connected NGO datasets to the platform using **REST APIs + Python**, enabling real-time dashboards and reducing manual reporting by **25%**  
🔹 Designed use cases, workflows, and BPMN diagrams for end-to-end feature implementation  
🔹 Built **Power BI dashboards** to monitor donation flows and operational costs

## 🚀 Projects

### 🏠 [Impact of Environmental & Social Factors on Real Estate Prices](https://github.com/Lalitsh03/Orange_County_Real_Estate_analysis)
*Independent Graduate Research · Cal State Fullerton*

Analyzed property transactions across **37 Orange County cities** to determine how environmental risks, school ratings, and economic indicators drive housing prices. Built 7 regression models with **~95% prediction accuracy**.

**Key Findings:**
- Walkability and school ratings outweigh luxury amenities in driving demand
- Air quality is the only environmental risk with statistically significant negative price impact (p<0.01)
- 36% seasonal price swing between Q1 and Q4

`Python` `Pandas` `Scikit-learn` `Statsmodels` `GeoPandas` `Web Scraping` `Excel`

### 🌆 [Property Tax & Crime Dynamics in Boston](https://github.com/Lalitsh03/Boston_Crime_with_Property_Analysis)
*Capstone Project · Cal State Fullerton*

Investigated the correlation between property gross tax and crime rates across **11 Boston neighborhoods** using 61K+ merged records from three public datasets. Built an OLS regression model achieving **99.75% R²** on unseen data.

**Key Findings:**
- **-0.37 Pearson correlation** between property taxes and crime (statistically significant, p = 0.001)
- East Boston: highest crime (33K incidents), below-average taxes
- Boston & Charlestown: highest taxes, lowest crime, safest for investment

`Python` `Pandas` `Scikit-learn` `Statsmodels` `Seaborn` `SciPy` `Alteryx` `R`

### 🏥 Disease Prediction System (Healthcare ML)

Developed an ML-based diagnostic system to predict diseases from user symptoms. Boosted model accuracy by **20% through feature engineering** (Decision Trees/ANN) and deployed through a **Django web interface**.

`Python` `Scikit-learn` `Django` `K-Fold Cross-Validation`

### 🚗 CommuteLink — Real-Time Transportation App Concept

Designed workflow, architecture, and real-time routing logic for a commuter mobility platform. Created **UI flows, WBS, Gantt charts, and cloud-backed routing logic** for prototype planning.

## 🎓 Education

**M.S. in Management Information Systems**  
California State University, Fullerton — Jan 2025

**B.E. in Electronics & Telecommunication Engineering**  
Himachal Pradesh Technical University, Hamirpur (H.P.), India — May 2022

## 📫 Let's Connect

[![Email](https://img.shields.io/badge/Email-sh.lalit007%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sh.lalit007@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-lalitsharmacsuf-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lalitsharmacsuf/)
[![Phone](https://img.shields.io/badge/Phone-(858)%20230--1074-34d399?style=for-the-badge&logo=phone&logoColor=white)](#)
