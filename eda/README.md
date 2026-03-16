# ⚽ FIFA Players Dataset - Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a **FIFA Players dataset** using **Python and Pandas**. The main objective is to understand the structure of the dataset, clean the data, and extract meaningful insights about football players such as their **age, nationality, club, ratings, and financial attributes**.

The dataset contains information about **18,000+ football players**, including attributes like **overall rating, potential, club, wage, and market value**.

---

# 📂 Dataset Information

The dataset contains **18,207 rows and 18 columns**.

## Key Columns

* **ID** – Unique player identifier
* **Name** – Player name
* **Age** – Player age
* **Nationality** – Country of the player
* **Overall** – Overall rating of the player
* **Potential** – Potential future rating
* **Club** – Player's club
* **Value** – Market value of the player
* **Wage** – Weekly wage
* **Preferred Foot** – Left or right foot preference
* **International Reputation** – Player reputation rating
* **Skill Moves** – Skill rating
* **Position** – Playing position
* **Joined** – Year the player joined the club
* **Contract Valid Until** – Contract expiration year
* **Height** – Player height
* **Weight** – Player weight
* **Release Clause** – Release clause value

---

# 🛠 Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook / VS Code**

---

# 🔎 EDA Steps Performed

## 1️⃣ Data Loading

The dataset was loaded using **Pandas**.

```python
import pandas as pd

df = pd.read_csv("fifa_players.csv")
```

---

## 2️⃣ Data Inspection

Basic information about the dataset was explored.

* `df.head()` → View first rows
* `df.info()` → Data types and missing values
* `df.shape` → Dataset size
* `df.describe()` → Statistical summary

---

## 3️⃣ Handling Missing Values

Missing values were identified and handled using techniques such as:

* Dropping unnecessary columns
* Filling missing values with **mean / median / mode**
* Removing incomplete rows when necessary

---

## 4️⃣ Data Cleaning

Data cleaning steps included:

* Converting incorrect data types
* Handling inconsistent values
* Removing duplicate records
* Formatting numerical columns like **Value, Wage, and Release Clause**

---

## 5️⃣ Data Exploration

Key insights explored during analysis:

* Distribution of **player ages**
* **Top players** based on overall rating
* **Most common nationalities**
* **Club-wise player distribution**
* Relationship between **Overall Rating and Potential**

---

# 📊 Example Analysis Questions

Some questions explored during the analysis include:

* What is the **average age of players**?
* Which **countries produce the most players**?
* Who are the **top-rated players**?
* Which **clubs have the highest valued players**?
* How does **potential compare to overall rating**?

---

# 📈 Possible Visualizations

The following visualizations can be created:

* **Age distribution histogram**
* **Top nationalities bar chart**
* **Player rating scatter plots**
* **Club-wise player count charts**

---

# 🎯 Project Goal

The goal of this project is to:

* Practice **data cleaning and preprocessing**
* Understand **real-world sports datasets**
* Perform **Exploratory Data Analysis using Pandas**
* Generate **meaningful insights from football player data**

---

# 📌 Conclusion

The EDA process helps uncover patterns in the **FIFA players dataset**, such as player ratings, nationality distribution, and financial attributes. These insights can be useful for **sports analytics, scouting, and player performance evaluation**.

---
