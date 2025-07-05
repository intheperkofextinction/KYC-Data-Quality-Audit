
#  KYC Onboarding Data Audit & Risk Flagging

This project simulates and audits client onboarding (KYC) data to identify quality issues, detect compliance risks, and visualize insights using Python and PowerPoint.

---

##  Project Overview

In financial institutions, poor-quality KYC (Know Your Customer) data can lead to serious compliance failures. This project simulates realistic onboarding data and applies rule-based logic to flag anomalies like:

- Missing Full Names, ID Numbers, Aadhaar, PAN
- Incomplete KYC status
- Misspelled country names
- Onboarding from high-risk countries

---

## 🛠 Tools & Libraries Used

| Tool / Library      | Purpose                            |
|---------------------|------------------------------------|
| `pandas`            | Data manipulation and cleaning     |
| `Faker`             | Generate synthetic client data     |
| `random`            | Controlled randomness              |
| `pycountry`         | Real country validation list       |
| `rapidfuzz`         | Fuzzy string matching (country fix)|
| `matplotlib`        | Basic data visualization           |
| PowerPoint (PPT)    | Final report presentation          |

---

##  Data Generation

The dataset was generated using `Faker`, mimicking 500 onboarding records across:

- Names
- Client IDs
- Date of Birth
- ID Number & Type
- Country (with occasional typos or risky nations)
- Aadhaar/PAN (for Indian residents)
- Account Type (Retail / Corporate / HNI)

Each record was tagged based on rule-based flagging logic.

---

##  Analysis Performed

- Missing value summary
- Rule-based flag generation for compliance issues
- Country name cleaning using fuzzy matching
- Risk pattern analysis across account types
- Visualization of flagged issues using bar charts
- Insights summarized in a final report

---

## 🖥 Report Presentation

A clean and modern PowerPoint report was prepared to showcase:

- Key issues identified
- Breakdown by account type
- Suggested areas for improvement
- Summary of methods used

---

## 📁 Files in This Repository

- `kyc_data_generator.ipynb` → Python notebook for data simulation  
- `kyc_audit_analysis.ipynb` → Python notebook for cleaning, flagging, and visualizing  
- `kyc_onboarding_data.csv` → Generated dataset  
- `KYC_Data_Audit_Presentation.pptx` → Final PowerPoint report  
- `README.md` → This file

---

## 📬 Contact

**Amal S.**  
📧 amal17ek@gmail.com  
🔗 linkedin.com/in/amal-s-9a5b86310 


---

> ⚠️ *This project uses synthetic data and is for learning/demo purposes only.*
