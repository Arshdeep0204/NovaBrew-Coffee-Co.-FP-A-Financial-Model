# NovaBrew-Coffee-Co.-FP-A-Financial-Model
Tools: Excel (Advanced)  |  Sector: Food & Beverage / QSR  |  Period: FY 2024-25  |  Currency: ₹ Thousands (₹K)

Project Overview
This is a self-initiated FP&A portfolio project simulating the financial planning and analysis function of a 12-outlet specialty coffee chain operating across Delhi-NCR. The model covers a full fiscal year (April 2024 – March 2025) and replicates the core workflow of a junior FP&A analyst — building the budget, tracking actuals, forecasting forward, and explaining variances to management.
The project is structured around 5 connected Excel sheets, each representing a distinct layer of the FP&A cycle.

Business Context
ParameterDetailCompanyNovaBrew Coffee Co. (simulated)IndustryFood & Beverage — Specialty Coffee / QSRGeographyDelhi-NCR, India — 12 OutletsFiscal YearFY 2024-25 (April 2024 – March 2025)Revenue Scale₹19,903K (~₹2 Crore)Revenue StreamsIn-Store Product Sales, Delivery & Online, B2B Corporate, Merchandise

Project Structure
NovaBrew_FPA_Model/
│
├── NovaBrew_FPA_Model_v2_Professional.xlsx
│   ├── Sheet 1 — Historical P&L
│   ├── Sheet 2 — Budget Model
│   ├── Sheet 3 — Forecast Model
│   ├── Sheet 4 — Variance Analysis
│   └── Sheet 5 — Executive Dashboard
│
└── README.md

Sheet-by-Sheet Breakdown
1. Historical P&L (Income Statement)
The foundation of the model. Structured as a simplified monthly income statement covering all 12 months of FY 2024-25.
Structure:

Revenue → 4 streams with monthly breakdown
Cost of Goods Sold → Gross Profit → Gross Margin %
Operating Expenses → 6 line items (Rent, Salaries, Marketing, Utilities, Logistics, Admin)
EBITDA → EBITDA Margin % (monthly and full-year)

Key outputs:

Total Revenue: ₹19,903K
Gross Margin: 67.6%
EBITDA: ₹6,056K at 30.4% margin
EBITDA margin expanded from 27.0% (Jan) to 34.2% (Dec) — positive operating leverage


2. Budget Model
The planned financial performance for FY 2024-25 — the management commitment made at the start of the year.
Structure mirrors the P&L with two additions:

Fixed vs. Variable cost classification on every expense line
Full-year totals with % of Revenue column

Fixed costs: Rent (₹1,485K), Salaries (₹2,675K), Admin (₹546K)
Variable costs: Marketing (₹840K), Logistics (₹1,241K)
Semi-variable: Utilities (₹478K)
Key outputs:

Budgeted Revenue: ₹19,735K
Budgeted EBITDA: ₹6,067K at 30.7% margin


3. Forecast Model (Driver-Based, 3 Scenarios)
A rolling forecast where H1 (Jan–Jun) is locked to actuals and H2 (Jul–Dec) is projected using stream-level monthly growth assumptions.
Forecasting methodology:

Each revenue stream has its own MoM growth rate (not one flat rate)
Expense lines forecast independently based on cost-specific drivers
H1 actuals locked — forecast only moves H2 forward

Growth assumptions used:
StreamH2 Growth RateProduct Sales2.5% MoM (Jul–Sep), 3.0% (Oct–Dec)Delivery & Online2.2% MoMB2B Corporate1.8% MoMMerchandise3.0% MoM
Three scenarios:
ScenarioLogicFull-Year RevenueBase CaseStream-level growth assumptions₹19,632KBull CaseBase × 1.05 applied to H2₹20,163KBear CaseBase × 0.94 applied to H2₹18,994K
Revenue range across scenarios: ₹1,169K spread

4. Variance Analysis
The most analytical sheet. Compares Budget vs. Actual for the full year with root-cause commentary, plus a Month-over-Month trend section.
Section A — Full-Year Budget vs. Actual:
Line ItemBudgetActualVarianceF/UTotal Revenue₹19,735K₹19,903K+₹168K▲ FAVCOGS₹6,403K₹6,454K+₹51K▼ UNFAVGross Profit₹13,332K₹13,449K+₹117K▲ FAVTotal OpEx₹7,265K₹7,393K+₹179K▼ UNFAVEBITDA₹6,067K₹6,056K−₹11K▼ UNFAV
Root causes identified:

Revenue beat (+₹168K): Delivery channel outperformed (+3.9% vs plan), festive Q4 uplift
COGS miss (+₹51K): Arabica bean prices rose ~4.2% YoY — external, commodity risk
Marketing miss (+₹34K, +4.0%): Digital brand campaigns in Aug–Sep exceeded plan
Logistics miss (+₹28K, +2.3%): Route inefficiencies in Q2, corrected post-October
Net result: Revenue outperformance fully offset by cost pressures → EBITDA missed by ₹11K

Section B — Month-over-Month (MoM):

Revenue grew every single month (12/12 months FAV on MoM basis)
July showed softest growth (+0.3% MoM) — post-monsoon demand slowdown
December strongest at +8.6% MoM — festive season peak


5. Executive Dashboard
A CFO-facing summary sheet — everything a senior leader needs in one view without drilling into detail tabs.
Three sections:
KPI Cards: Total Revenue, Total Expenses, Gross Profit, EBITDA, Revenue Variance, EBITDA Variance — headline numbers at a glance
Variance Bridge Table: Every P&L line with Budget, Actual, Variance ₹K, Var%, and FAV/UNFAV flag — color-coded green/red
Monthly Trend Table: 12-month view of Budget vs. Actual across Revenue, Expenses, EBITDA, and EBITDA Margin % — shows when variances occurred

Key Findings

Top-line beat, bottom-line miss — Revenue outperformed budget by ₹168K but EBITDA still missed by ₹11K because cost pressures (₹179K OpEx overrun) exceeded the revenue upside
COGS is the external risk — Arabica bean inflation (+4.2% YoY) is uncontrollable; needs vendor contract renegotiation or menu price adjustment in FY26
Marketing is the controllable risk — ₹34K overspend (+4.0%) on digital campaigns with no corresponding revenue outperformance in the same months (Aug–Sep revenue was actually below plan)
Operating leverage is real — EBITDA margin expanded from 27.0% in January to 34.2% in December, showing fixed costs being absorbed as revenue scales
Bear Case still profitable — Even in the worst-case scenario (−6% on Base H2), the business generates positive EBITDA, confirming the cost structure is resilient

FP&A Concepts Demonstrated

Budget vs. Actual variance analysis with root-cause commentary
Driver-based rolling forecast (stream-level, not flat rate)
Scenario planning — Base / Bull / Bear
Fixed vs. variable cost classification
Gross margin and EBITDA margin tracking
Operating leverage analysis
Month-over-Month trend analysis
Management reporting pack structure (Executive Dashboard)
