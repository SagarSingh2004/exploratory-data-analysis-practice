# 🦈 Shark Tank India – Season 1  
## Exploratory Data Analysis (EDA)

---

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Shark Tank India Season 1 dataset.

The main objective is to analyze:

- Investment patterns
- Deal structures
- Shark participation
- Equity and valuation trends
- Episode-wise funding behavior

The dataset contains 117 startup pitches along with detailed deal and shark participation information.

---

## 📂 Dataset Columns

The dataset includes the following columns:

- `episode_number` – Episode in which the pitch was presented  
- `pitch_number` – Pitch number within the episode  
- `brand_name` – Name of the startup  
- `idea` – Business idea description  
- `deal` – Whether a deal was made (1 = Yes, 0 = No)  
- `pitcher_ask_amount` – Amount requested by the entrepreneur (in lakhs)  
- `ask_equity` – Equity percentage requested by the entrepreneur  
- `ask_valuation` – Valuation requested by the entrepreneur  
- `deal_amount` – Final investment amount (in lakhs)  
- `deal_equity` – Final equity given to sharks  
- `deal_valuation` – Final company valuation after negotiation  

### Shark Presence Columns (Episode-Level)

- `ashneer_present`  
- `anupam_present`  
- `aman_present`  
- `namita_present`  
- `vineeta_present`  
- `peyush_present`  
- `ghazal_present`  

### Shark Deal Participation Columns (Pitch-Level)

- `ashneer_deal`  
- `anupam_deal`  
- `aman_deal`  
- `namita_deal`  
- `vineeta_deal`  
- `peyush_deal`  
- `ghazal_deal`  

### Derived Columns

- `total_sharks_invested` – Number of sharks investing in the deal  
- `amount_per_shark` – Investment amount per shark  
- `equity_per_shark` – Equity percentage per shark  

---

## 🛠 Tools & Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🧹 Data Cleaning Steps

- Checked and handled missing values  
- Verified duplicate records  
- Converted required columns to correct data types  
- Treated no-deal cases appropriately (deal_amount and deal_equity set to 0 where necessary)

---

## 📊 Key Insights

- 65 out of 117 pitches received funding (55.56% success rate).
- Average deal amount: ₹57.57 lakhs.
- Median deal amount: ₹50 lakhs.
- Total investment across the season: ₹37.42 crores.
- Aman, Peyush, and Anupam made the highest number of investments.
- Ask valuation and deal valuation show a positive correlation (0.66).
- Deal equity and valuation show a negative correlation (-0.51).
- In 10 cases, sharks invested more than the asked amount, usually in exchange for higher equity.
- Smaller funding requests had a higher probability of getting funded.
- Investment activity varied significantly across episodes.

---

## 📈 Conclusion

The analysis shows that shark investments are negotiation-driven and opportunity-based.

- Higher equity generally leads to lower valuation.
- Realistic funding expectations improve deal success.
- Investment decisions depend more on pitch quality than episode sequence.

This project demonstrates practical skills in data cleaning, visualization, correlation analysis, and business insight generation.

---

## 📂 Project Structure

Shark-Tank-India-EDA/
│
├── Shark_Tank_India_EDA.ipynb
├── EDA_Shark_Tank_India.xlsx
└── README.md

---

## 👨‍💻 Author

Sagar Singh
Aspiring Data Scientist