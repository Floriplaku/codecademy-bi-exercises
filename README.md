# 📂 Other Mini-Projects

This folder contains smaller Codecademy Python projects that explore **dictionaries** and **conversion funnels** in data analysis.

---

## 🏥 U.S. Medical Insurance – Dictionaries Project

### 📌 Project Description
This project uses **Python dictionaries** to simulate and manage U.S. medical insurance data.  
It demonstrates how to store, access, and analyze patient information using dictionaries and list comprehensions.

### ⚙️ Main Steps
1. **Store patient data**  
   - Created a dictionary with patient names and insurance costs.  
   - Extended dictionary with additional attributes (age, sex, BMI, children, smoking).  

2. **Compute averages**  
   - Calculated average insurance cost using dictionary values.  

3. **List comprehension**  
   - Built a new dictionary linking patients to their ages.  
   - Extracted subsets of patients (e.g., smokers, high BMI).  

### 🔑 Key Questions Explored
- How can dictionaries be used to store structured data efficiently?  
- How do we calculate statistics (averages) from dictionary values?  
- How can we extend dictionaries with list comprehensions?  

### 📊 Tools Used
- **Python basics**: dictionaries, lists, loops  
- **List comprehensions** for quick data transformation  

---

## 📈 Page Visits Funnel Project

### 📌 Project Description
This project analyzes an e-commerce **conversion funnel** using event log data.  
The dataset contains user activity at different steps: visits, cart, checkout, and purchase.  
The goal is to calculate conversion rates and identify where users drop off in the funnel.

### ⚙️ Main Steps
1. **Load and clean data**  
   - Imported CSV files with user activity logs.  
   - Merged data on user IDs to track full funnel behavior.  

2. **Analyze conversion steps**  
   - Calculated % of users who visited → added to cart → checked out → purchased.  
   - Identified drop-off points (e.g., users who abandoned cart).  

3. **Time-to-purchase analysis**  
   - Computed average time between visiting the site and completing purchase.  

### 🔑 Key Questions Explored
- What percentage of visitors actually purchase an item?  
- At which funnel step do most users drop off?  
- How long does it take for an average user to make a purchase?  

### 📊 Tools Used
- **Pandas** for data manipulation  
- **Datetime operations** for calculating time-to-purchase  
- **Conversion metrics** for funnel analysis  
