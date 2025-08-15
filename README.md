# Cancer Diagnosis Insights - Excel Dashboard

## 🔍 Key Questions Answered

### 📊 Patient Demographics
- Age peaks: 45-54 (32% of cases)  
- Females showed 20% higher Stage I diagnoses  
- Top 3 countries: Nigeria (42%), Ghana (23%), Kenya (18%)  
- BMI trend: Men 50+ averaged 28.4 (overweight threshold)  

### 🩺 Diagnosis & Staging  
- Late-stage (III/IV) dominated in rural clinics (55% vs urban 32%)  
- New diagnoses ↑ 12% YoY  
- Avg diagnosis age: Stage I=49, Stage IV=63  

### 🚬 Risk Factors 
- Smokers: 3x more likely Stage IV  
- 18% had family history  
- Hypertension in 34% of Stage III+ patients  

### 💊 Treatment Patterns 
- Surgery + chemo = 62% of Stage II cases  
- Avg treatment duration: Stage I=6mo, Stage IV=18mo  
- Combined therapy survival ↑ 40% vs single treatment  

### 📈 Outcomes 
- 5-year survival: Stage I=82%, Stage IV=23%  
- Nigeria survival rate lagged by 15% vs regional avg  

---

## 🛠️ How I Built This 
Tools: Excel + Power Query  
Process:  
1. Cleaned 15K+ records (fixed staging labels, imputed missing BMI)  
2. Created dynamic pivot tables with age/stage filters  
3. Built dashboard with slicers for country/risk-factor drill-downs  

![Dashboard Preview](excel_dashboard.png)

---

## 📂 Files 
- `Cancer_Analysis.xlsx` (Full dashboard + raw data tab)  
- `Data_Dictionary.pdf` (Column definitions + cleaning steps)  

## 🔜 Next Steps  
1. Automate WHO data imports with Power BI  
2. Add survival rate calculators  
3. Build clinic-specific error reports  
