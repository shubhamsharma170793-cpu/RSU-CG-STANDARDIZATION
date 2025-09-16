# Proposal: Industry-Wide Standard for RSU Capital Gains Reporting  

## 1. Background  
Restricted Stock Units (RSUs) are a common component of employee compensation, especially in multinational corporations.  
- Upon vesting, RSUs are taxed as **perquisites** in India under Section 17(2) of the Income Tax Act.  
- On sale, they trigger **capital gains taxation**, requiring precise reporting in **Schedule CG** of the Income Tax Return (ITR).  

### Current Challenge  
Each broker (e.g., Morgan Stanley, E*TRADE, Fidelity, internal SAP brokerages) provides CSV/PDF reports in **different formats**. Employees must manually reformat them to fit Schedule CG requirements, often resulting in dozens of manual entries.  

---

## 2. Problem Statement  
- **Manual Data Entry Burden** → Employees may have 30–40 acquisition dates for a small number of RSUs.  
- **Inconsistent Reporting** → Broker reports vary in fields, units, and formats.  
- **High Error Risk** → Misreporting dates, FMV, or fractional shares leads to incorrect tax liability.  
- **Low Compliance Incentive** → Brokers are not obligated to provide ITR-compatible exports.  
- **Dependency on Professionals** → Most employees rely on CAs, but even professionals often misreport RSU data due to complexity.  

---

## 3. Proposed Solution  
Introduce a **standardized RSU Capital Gains Export Schema** (CSV/JSON) aligned with Schedule CG.  

Precedents already exist:  
- **Contract Note Format** standardized by SEBI for equity trades.  
- **Consolidated Account Statement (CAS)** for mutual funds via AMFI.  

**Key idea:**  
- Brokers generate exports in a consistent format.  
- Employees can directly upload to the Income Tax portal or third-party platforms.  
- Filing becomes a **zero-manual-intervention process**.  

---

## 4. Implementation Roadmap  
1. **CBDT Notification** → Issue mandate requiring all brokers offering RSU custodial services to adopt the standard.  
2. **Broker Integration** → Brokers update systems to auto-generate exports.  
3. **Portal Integration** → Income Tax e-filing utility enables direct upload; third-party platforms adopt it.  
4. **Employee Experience** → Download → Upload → Done ✅  

---

## 5. Benefits  
- **Employees** → No manual mapping, fewer errors, smoother compliance.  
- **Brokers** → Reduced employee queries, uniform compliance.  
- **Tax Platforms** → One standard → universal support.  
- **Government** → Cleaner, structured data → higher compliance and better analytics.  

---

## 6. Precedents in India  
- **Contract Note Standardization** (SEBI).  
- **CAS Mutual Funds** (AMFI + SEBI).  
- **Form 26AS & AIS** (CBDT → standard digital tax reporting).  

---

## 7. Call to Action  
We propose that **CBDT in collaboration with SEBI and NASSCOM**:  
1. Publish the RSU Capital Gains Reporting standard.  
2. Mandate broker compliance by FY 2026.  
3. Ensure integration with ITR utilities and leading tax filing platforms.  

The goal is to make RSU reporting as smooth as downloading and uploading **Form 26AS or CAS** today.  
