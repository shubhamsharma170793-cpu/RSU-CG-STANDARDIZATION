# Proposal: Industry-Wide Standard for RSU Capital Gains Reporting  

## 1. Background  
Restricted Stock Units (RSUs) are a common component of employee compensation, especially in multinational corporations.  

- Upon vesting, RSUs are taxed as **perquisites** under Section 17(2) of the Income Tax Act.  
- On sale, they trigger **capital gains taxation**, requiring reporting in **Schedule CG**.  

### Current Challenge  
- Broker reports are inconsistent across platforms (Morgan Stanley, Fidelity, E*TRADE, SAP Internal, etc.).  
- Employees must manually reformat reports to match Schedule CG.  
- Fractional shares, multiple acquisition dates, and varying cost basis calculations increase complexity.  

---

## 2. Problem Statement  
- **Manual data entry burden:** One sale may require 30–40 rows.  
- **High error risk:** Misreporting FMV, acquisition dates, or fractional shares.  
- **Low compliance incentive:** Brokers are not obliged to provide ITR-compatible data.  
- **Dependency on professionals:** Even experienced CAs may misfile RSU transactions due to complexity.  

---

## 3. Proposed Solution  
- **Standardized RSU Export Schema** (CSV/JSON) aligned with Schedule CG.  
- Brokers auto-generate exports directly compatible with e-filing platforms.  
- Third-party tax platforms support direct upload.  
- Employees experience **zero manual intervention**.  

---

## 4. Implementation Roadmap  
1. **Regulatory Mandate:** CBDT/SEBI notification requiring all RSU brokers to adopt standard schema.  
2. **Broker Integration:** System updates to auto-generate standardized exports.  
3. **Platform Integration:** Tax filing platforms accept uploads from standardized schema.  
4. **Employee Experience:** Download → Upload → Done.  
5. **Monitoring & Feedback:** Collect adoption metrics, error rates, and continuous improvement.  

---

## 5. Stakeholder Impact  
| Stakeholder       | Benefit                                                                 |
|------------------|------------------------------------------------------------------------|
| Employees         | Reduced manual work, fewer errors, improved compliance                  |
| Brokers           | Reduced queries, uniform compliance, easier audit                        |
| Tax Filing Platforms | Simplified ingestion, consistent data format                            |
| Government       | Cleaner data, increased tax compliance, streamlined reporting            |

---

## 6. Precedents in India  
- **Contract Note Standardization (SEBI)** for equity trades  
- **Consolidated Account Statements (AMFI/SEBI)** for mutual funds  
- **Form 26AS & AIS (CBDT)** for digital tax reporting  

---

## 7. Call to Action  
- CBDT, SEBI, and industry bodies (e.g., NASSCOM) should:  
  - Publish the RSU Capital Gains Reporting Schema as a mandatory standard.  
  - Mandate broker compliance by FY 2026.  
  - Ensure integration with ITR e-filing and leading third-party tax platforms.  

- **Goal:** Make RSU reporting as simple as downloading Form 26AS or CAS statements today.
