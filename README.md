# Financial Modeling Portfolio

Two self-built financial models covering the core valuation and transaction skill sets used in financial analyst, business analyst, and credit/risk roles. Each is built from scratch in Excel, fully formula-driven (no hardcoded outputs), sourced from company annual reports, and documented in-sheet.

**Harsahib Singh** · B.A. (Hons) Economics, SGGSCC, University of Delhi · FRM Part 1 candidate (Nov 2026)
📧 harsahib2004@gmail.com · [LinkedIn](https://www.linkedin.com/in/harsahib-singh-7b9308289)

---

## 1. Reliance Industries — 3-Statement Model & DCF Valuation
📄 `RIL_3Statement_DCF_Model.xlsx` · `RIL_DCF_Valuation_Report.docx`

A fully-linked three-statement model (Income Statement, Balance Sheet, Cash Flow) on FY23–FY26 historicals with five-year projections, an integrated debt schedule with circular interest, and a DCF valuation.

| Metric | Value |
|---|---|
| WACC | 11.68% (Rf 6.85%, Beta 0.94, ERP 6.5%) |
| Implied share price | ₹1,533 |
| Market price (31 Mar 2026, date-matched) | ₹1,369 |
| Premium to market | +12.0% |
| Terminal value as % of EV | ~75% |

Includes a two-way WACC × terminal-growth sensitivity table and a comparable-companies cross-check. The DCF is compared to the market price **on the same date as the underlying balance sheet**, since a model's fair value is only as current as its inputs. The accompanying report documents methodology, findings, and known limitations.

## 2. Ajanta Pharma — Leveraged Buyout (LBO) Model
📄 `Ajanta_Pharma_LBO_Model.xlsx`

An illustrative leveraged buyout on FY23–FY26 historicals, covering transaction structuring through to sponsor returns.

| Parameter | Value |  | Result | Value |
|---|---|---|---|---|
| Entry / Exit multiple | 9.0x / 9.0x |  | Entry EV | ₹14,102 cr |
| Leverage | 7.0x EBITDA |  | Exit EV | ₹22,911 cr |
| Capital structure | 76% debt / 24% equity |  | MOIC | 5.25x |
| Hold period | 5 years |  | IRR | 39.3% |

Includes sources & uses, purchase-price allocation with goodwill, a debt schedule with 100% cash sweep, a full returns bridge, and two-way sensitivity tables (IRR by entry × exit; MOIC by leverage × exit).

**On the entry multiple:** Ajanta actually trades at ~24–26x EV/EBITDA. The 9.0x entry here is *deliberately illustrative*, chosen so the deal can support a realistic debt-heavy LBO structure — itself a real finding, since premium high-growth companies are uncommon LBO targets. This is documented in the model, not hidden.

---

## Approach

- **Real data** — historicals sourced line-by-line from published annual reports and reconciled against the reported statements.
- **Fully linked** — no hardcoded projection outputs; every figure traces to an assumption. Circular references (interest ↔ debt ↔ cash flow) resolve via iterative calculation.
- **Documented** — methodology, conventions (e.g. cash-free/debt-free), and known simplifications are noted in-sheet so a reviewer can follow the reasoning, not just the result.

**Skills:** `3-Statement Modeling` · `DCF Valuation` · `LBO Modeling` · `WACC` · `Sensitivity Analysis` · `Comparable Companies` · `Excel` · `Financial Statement Analysis`

> **How to open:** use Excel with iterative calculation enabled (File → Options → Formulas → Enable iterative calculation) so the debt/interest circularity resolves on load.

---

*These are illustrative, educational models built for skill demonstration. They are not investment advice, not a recommendation regarding any security, and the entry assumptions (particularly the LBO entry multiple) are deliberately illustrative rather than reflective of actual market pricing.*
