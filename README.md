# 📊 Pokémon Exploratory Data Analysis (EDA)

<img width="578" height="327" alt="image" src="https://github.com/user-attachments/assets/12a5492f-b431-427e-a410-a0695da8ecc2" />

## 📌 Overview
This project performs an **exploratory data analysis (EDA)** on a Pokémon dataset containing detailed information about various species, including their **types**, **base stats**, **legendary status**, and **generation**.  

The goal is to uncover patterns in Pokémon characteristics, compare single vs. dual types, analyze stat distributions, and explore relationships between features.

---

## 🎯 Questions
- Which Pokémon types are the most common?  
- How do Single-Type and Dual-Type Pokémon compare in distribution?  
- Which types have the highest and lowest average base stats?  
- Are Legendary Pokémon significantly stronger than non-Legendaries?  
- How are stats distributed across different generations?  
- Is there a relationship between having two types and total stats?  

---

## 📂 Dataset
- **Rows:** 801 Pokémon species  
- **Columns:** 41 attributes including:
  - **Identifiers:** Pokédex number, name, generation, legendary flag
  - **Types:** `type1` and `type2`
  - **Base Stats:** HP, Attack, Defense, Special Attack, Special Defense, Speed
  - **Type Effectiveness:** `against_*` multipliers
  - **Physical Attributes:** Height, Weight, Gender ratio
  - **Abilities:** Possible ability lists per Pokémon

---

## 🔍 Key Insights
- **Type Distribution:** Water is the most common primary type, while Flying dominates as a secondary type.  
- **Strongest Types:** Dragon and Steel consistently rank highest across multiple stats.  
- **Weakest Types:** Bug, Poison, and Normal tend to have the lowest average stats.  
- **Legendary Pokémon:** Only ~8.7% of species are Legendary; Dragons and Psychics are the most common legendary types.  
- **Dual Types:** ~52% of Pokémon are dual-typed, with Steel and Rock having the highest dual-type percentage.  
- **Stat Patterns:** Most stats cluster around a mean of ~70 with extreme outliers >200.

---

## 📊 Visualizations
- **Type Distributions:** Bar charts for primary and secondary types.
- **Strongest/Weakest Types:** Heatmap comparing type performance across stats.
- **Legendary Analysis:** Pie + bar plots for Legendary vs. Non-Legendary distribution.
- **Dual-Type Analysis:** Pie + bar plots and percentage breakdown by type.
- **Stat Distributions:** Histograms and mean/median overlays per type.

---

## 🛠️ Tech Stack
- **Python**
- **Pandas** – Data cleaning and manipulation
- **Matplotlib & Seaborn** – Data visualization
- **Colab Notebook**
