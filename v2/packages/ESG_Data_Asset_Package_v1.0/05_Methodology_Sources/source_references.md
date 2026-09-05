# Source references

Block ESG-DA-2026-001 - ESG_Data_Asset_Package_v1.0

| Id | Source | Type | Coverage | URL |
|----|--------|------|----------|-----|
| SRC-01 | National statistical agency - supply and use tables 2025 | statistical_agency | Inter-sector flows and gross output for all 10 sectors | https://data.example.org/io-tables/2025 |
| SRC-02 | Corporate sustainability reports (GRI-aligned), FY2025 | self_reported | Scope 1 and Scope 2 GHG emissions, turnover | https://reports.example.org/gri/2025 |
| SRC-03 | CSRD / ESRS regulatory filings, FY2025 | regulatory_filing | Own workforce characteristics (ESRS S1-6) | https://filings.example.org/esrs/2025 |
| SRC-04 | Independent assurance provider - limited assurance statements | third_party_audit | Verification status and confidence scores | https://assurance.example.org/2025 |

## Methodologies

- **MTH-01 Leontief input-output model** (Economic) - Leontief, W. (1986). Input-Output Economics, 2nd ed.. Technical coefficients A = Z / x; total requirements (I - A)^-1 for the 10-sector matrix.
- **MTH-02 GHG emissions disclosure** (GRI) - GRI 305: Emissions 2016 (305-1, 305-2). Scope 1 and Scope 2 (location-based) GHG emissions in tCO2e.
- **MTH-03 Employment and turnover disclosure** (GRI) - GRI 401: Employment 2016 (401-1); GRI 303: Water 2018 (303-3). New hires and turnover rate; water withdrawal by source.
- **MTH-04 Industry-specific metrics** (SASB) - SASB Standards, industry codes per sector (e.g. EM-MM-110a.1, TC-SI-130a.1). Sector metrics mapped to SASB industry codes.
- **MTH-05 Climate-related disclosures** (ISSB) - IFRS S2 Climate-related Disclosures. Cross-industry GHG metrics consistent with IFRS S2 paragraph 29(a).
- **MTH-06 European sustainability reporting** (CSRD) - ESRS E1-6 (GHG emissions), ESRS S1-6 (own workforce characteristics). Data points required under the CSRD delegated act.
- **MTH-07 Output-based valuation** (Valuation) - Internal valuation policy VP-2025-03. Token supply equals modelled output value in USD; one token represents one USD of output.
