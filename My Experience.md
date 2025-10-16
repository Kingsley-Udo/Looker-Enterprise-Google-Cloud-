# 🌟 My Experience with Looker Enterprise (Google Cloud)

## 📘 Project Overview
As a **Data Analyst**, I understand how powerful data visualization is in shaping data stories and driving decisions.  
For this project, I explored **Looker Enterprise (Google Cloud)** to build an interactive dashboard that analyzes **loan health data** from a **Fintech dataset**.  

The goal was to create a **user-friendly dashboard** that provides real-time insights into loan performance, customer profiles, and regional trends.  

---

## 🎯 Objectives
The main aim of this project was to help the analytics team:
- 💰 Identify the **total outstanding amount of all loans**  
- 📊 Analyze the **percentage of outstanding loans** across loan status categories  
- 🗺️ Discover **which states** have the highest number of outstanding loans  
- 👥 Find **customers who own their homes outright** and have active loans  

---

## 🧠 Dataset Information
**Dataset Name:** Fintech Dataset  
**Source:** Google Cloud preloaded dataset (available in Looker training environment)  

---

## ⚙️ Tools & Technologies
- 🧰 **Looker Enterprise (Google Cloud)**  
- 📄 **LookML** for data modeling  
- 🧮 **Google Cloud Platform** for hosting and exploration  
- 🎨 **Visualization types:** Single Value, Pie Chart, Column Chart, and Table  

---

## 🧩 Process & Steps

### 1️⃣ Setup
- Logged into Looker Enterprise with Google credentials  
- Created a new dashboard titled **“Loan Insights”** under the Developer Student’s folder  

### 2️⃣ Building Visualizations
#### 📈 Visualization 1: Total Outstanding Loans
- **Measure:** `Outstanding Loans Amount`  
- **Viz Type:** Single Value  
- Added a **threshold indicator** to highlight when the total > ₦3,000,000,000 (red background 🚨)

#### 🥧 Visualization 2: Percentage of Loans by Status
- **Dimension:** Loan Status  
- **Measure:** Outstanding Loans Amount  
- **Viz Type:** Pie Chart showing loan distribution across statuses  

#### 🗺️ Visualization 3: Top 10 States by Outstanding Loans
- **Dimension:** State  
- **Measure:** Outstanding Loans Amount  
- **Viz Type:** Column Chart  
- Filtered to display only the **Top 10 States** with highest loan totals  

#### 👥 Visualization 4: Top 10 Customers by Income
- **Dimensions:** Address State, Annual Income, Customer ID, Home Ownership, Interest Rate, Loan Status  
- **Viz Type:** Table  
- Filtered for customers who **own their homes outright** and **have current loans**

---

## 🔄 Added Functionality

### 🔁 Cross-Filtering
Enabled **cross-filtering** to allow interactive filtering between dashboard tiles — when a user clicks a value, other tiles dynamically adjust.

### ⏱️ Automatic Refresh Rates
- *Total Outstanding Loans* → Refresh **hourly**  
- *Top 10 Customers* & *Loan Status Breakdown* → Refresh **daily**  
- Entire Dashboard → Refresh **hourly** for real-time insights  

---

## 🎨 Dashboard Optimization
To make the dashboard intuitive and engaging:
- Applied a **consistent color palette**
- Organized charts into logical sections
- Added clear **titles and labels**
- Ensured a **responsive layout** for better user experience  

---

## 📊 Final Dashboard Snapshot
> *<img width="1363" height="636" alt="Looker Dashboard" src="https://github.com/user-attachments/assets/7cd1d897-5301-4d3a-881b-342b4fddb6d8" />*  

---

## 💡 Key Insights
- The dashboard gives an **instant overview** of the company’s loan portfolio health  
- Enables the team to **identify risks**, such as states with high loan exposure  
- Offers **customer segmentation** insights based on income and ownership  

---

## 📘 Learnings & Reflections
This project deepened my understanding of:
- 📚 **LookML modeling and Looker explores**
- 🧩 **Building cross-filtering interactions**
- 🎨 **Designing dashboards for clarity and impact**

It reminded me that great analytics is not just about numbers — it’s about crafting **stories that inspire action**. 💪  

---

## 🏷️ Tags
`#DataAnalytics` `#GoogleCloud` `#Looker` `#DataVisualization`  
`#BusinessIntelligence` `#PortfolioProject` `#DataStorytelling`

---

### 💬 Author
**Kingsley Onyegbule**  
*Data Analyst | Storyteller with Data | Continuous Learner*  
🔗 [Connect with me on LinkedIn](https://www.linkedin.com)  
🔗 [Explore my other projects on GitHub](https://github.com)

---

