# RSU Capital Gains Standardization  

*A product proposal to simplify RSU reporting in Indian Income Tax filings (Schedule CG).*  

---

## 📌 Overview  
Employees receiving **Restricted Stock Units (RSUs)** in India face major challenges during tax filing:  

- Broker exports come in inconsistent formats.  
- Manual re-entry into **Schedule CG** can require 30–40 rows for a single sale.  
- High risk of errors and dependency on Chartered Accountants.  

This repository proposes an **industry-wide standardized export schema** for RSU capital gains reporting. It’s a **product-focused solution** aimed at improving employee experience, reducing errors, and enabling better compliance.  

---

## 🚩 Problem  
- Inconsistent broker reports make filing time-consuming and error-prone.  
- Fractional shares and multiple acquisition dates add complexity.  
- Even professionals struggle to report accurately.  

---

## 💡 Proposed Solution  
- Standardized RSU Export Schema aligned with Schedule CG  
- Brokers auto-generate ITR-ready exports  
- Filing platforms support direct upload  
- Employees: **Download → Upload → Done ✅**  

---

## 📊 Example: Before & After  

**Current Broker Export (Before):**  

| Broker         | Employee_ID | Stock_Symbol | Security_Name | Vesting_Date | Sale_Date   | Quantity | FMV  | Sale_Price | Brokerage_Fee | Country |
|----------------|------------|--------------|---------------|-------------|------------|---------|------|------------|---------------|--------|
| Morgan Stanley | EMP123     | SAP          | SAP SE        | 15-07-2023  | 10-04-2024 | 0.257   | 2850 | 3200       | 50            | Germany |
| Morgan Stanley | EMP123     | SAP          | SAP SE        | 15-10-2023  | 10-04-2024 | 0.320   | 2900 | 3100       | 50            | Germany |
| Morgan Stanley | EMP123     | SAP          | SAP SE        | 15-01-2024  | 10-04-2024 | 0.423   | 2950 | 3250       | 50            | Germany |

**Standardized ITR-Ready Export (After):**  

| PAN        | Broker_Name    | ISIN          | Security_Name | Country | Quantity_Sold | Vesting_Date | Sale_Date   | FMV_at_Vesting | Cost_of_Acquisition | Sale_Consideration | Broker_Charges | Net_Proceeds |
|------------|---------------|---------------|---------------|---------|---------------|--------------|------------|----------------|-------------------|------------------|----------------|--------------|
| ABCDE1234F | Morgan Stanley | US1234567890 | SAP SE        | Germany | 0.257         | 15-07-2023   | 10-04-2024 | 2850           | 2850              | 3200             | 50             | 3150         |
| ABCDE1234F | Morgan Stanley | US1234567890 | SAP SE        | Germany | 0.320         | 15-10-2023   | 10-04-2024 | 2900           | 2900              | 3100             | 50             | 3050         |
| ABCDE1234F | Morgan Stanley | US1234567890 | SAP SE        | Germany | 0.423         | 15-01-2024   | 10-04-2024 | 2950           | 2950              | 3250             | 50             | 3200         |

---

## 📄 Whitepaper  
For detailed rationale, implementation roadmap, and industry perspective, see:  
[docs/whitepaper.md](docs/whitepaper.md)  

---

## 📜 License  
MIT — This repository and associated proposal can be freely referenced or shared for educational, research, or professional purposes.
