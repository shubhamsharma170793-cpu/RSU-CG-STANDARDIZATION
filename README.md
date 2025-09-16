# RSU-CG Standardization  
*A proposal for simplifying RSU reporting in Indian Income Tax filings (Schedule CG).*  

---

## 📌 Problem Statement  
Currently, reporting **Restricted Stock Unit (RSU)** transactions in Schedule CG (Capital Gains) of Indian ITR is highly complex:  

- RSUs are fractionated across multiple acquisition dates.  
- Taxpayers may need to enter **30–40 rows manually** for a single sale.  
- Brokers export data in different formats, making direct upload impossible.  
- Even Chartered Accountants often struggle with accurate filing.  

This leads to:  
- Wrong filings, causing compliance risks.  
- Extra cost & dependency on professionals.  
- Lost government revenue due to incorrect reporting.  

---

## 💡 Proposed Solution  
- Create a **standardized CSV/Excel template** for all brokers.  
- Brokers export directly in this format.  
- Filing platforms (Cleartax, government ITR portal, etc.) accept this as direct upload.  
- No manual intervention needed → **accuracy + simplicity**.  

---

## 📂 Repository Contents  
- `README.md` → Overview of the idea (this file).  
- `docs/whitepaper.md` → Detailed explanation of the proposal.  
- `examples/sample_broker_export.csv` → Example broker data.  
- `examples/mapped_itr_template.csv` → Same data transformed into ITR-ready format.  
- `src/mapping_specification.md` → Mapping rules & data definitions.  

---

## 🚀 Future Scope  
- Expand to cover **all equity-linked investments** (ESPP, stock options, mutual funds).  
- Collaborate with **brokers + ITR filing platforms + regulators** for adoption.  
- Reduce dependency on manual tax filing, improve compliance nationwide.  

---

## 🤝 Contribution  
This is an **open idea**. Contributions are welcome from:  
- Finance professionals  
- Tax consultants  
- Developers working with fintech/ITR platforms  
- Policy makers and industry bodies (e.g., NASSCOM, CBDT)  

---

## 📜 License  
This project is shared under the **MIT License** — free to use, adapt, and build upon.  
