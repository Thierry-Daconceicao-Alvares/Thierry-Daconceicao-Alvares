### Hi, I'm Thierry 👋

**AI & Data Specialist** | Applied AI · LLMs · Python · Business Intelligence | Procurement & Industrial Analytics

Paris area, France · Open to new opportunities, available now

I turn operational data into decision tools that teams actually adopt: reliable dashboards, automated data-quality controls and AI assistants for non-technical users, from requirements to rollout. Two years in the Purchasing department of Valeo Service (13 purchasing categories, 4 regions, 25 countries) and an MSc in Data & AI for Business.

#### Selected impact

- **72% fewer price anomalies in a few weeks** (6,894 → 1,964) with a price-discrepancy tracker I designed and built: weekly reconciliation of 3 sources across 15 divisions and about 145,000 items, business rules and 3-level escalation.
- **€74.6M of spend steered from one dashboard**: procurement business plan over a 12-month rolling window, 100+ suppliers and 36 months of history, with actuals vs budget, forecasts and variance analysis. Adopted as the team's reference.
- **2,010 compliance checkpoints monitored**: supplier compliance dashboard (134 suppliers × 15 documents) with 30/60/90-day alerts.
- **AI adoption**: AI referent of the Purchasing function. Designed a multi-LLM document-review agent calibrated with few-shot examples from real reviewer corrections, with an estimated 60% of review time saved (in testing).

#### Featured projects

| Project | Highlights | Try it | Stack |
|---|---|---|---|
| [**Invoice Block Radar**](https://github.com/Thierry-Daconceicao-Alvares/invoice-block-radar) | Payment blocks in purchase-to-pay, on a real event log (251,734 order lines, 1.6M steps): process mining shows 22% of lines blocked and 65% of blocks released with nothing corrected; each new order line gets a risk score from the vendor's live block history (checking the riskiest 20% catches 34% of future blocks, against 20% for a random check, on months never used to choose it); a detective sorts blocked invoices with rules and drafts the vendor email with Mistral, every figure checked in code; two LightGBM models lost to this simple rate every month and are shown as such | [Live demo](https://invoice-block-radar.vercel.app) | dbt · DuckDB · PM4Py · LightGBM · Mistral · FastAPI · Next.js · ECharts |
| [**NEXORA AI**](https://github.com/Thierry-Daconceicao-Alvares/nexora-ai) | AI-assisted review of purchase requests: seven purchasing rules in code, an LLM that explains findings citing only the policy passages it was given, every citation, figure and quotation verified in code, decisions by people with a full audit trail, email intake and notifications through n8n; evaluated on 153 held-out requests, failures included | [Live demo](https://nexora-procurement.streamlit.app) | Python · FastAPI · PostgreSQL · Mistral · Streamlit · n8n · Docker |
| [**AI Procurement Intelligence**](https://github.com/Thierry-Daconceicao-Alvares/ai-procurement-intelligence) | Spend analytics, anomaly detection and supplier risk on 1.5M French public contracts (open data): records merged and implausible amounts set aside, LightGBM model of expected amounts, spend classification, alerts explained by an LLM with every figure verified, decisions in an audit log; Power BI report on the same data | [Live demo](https://ai-procurement-intelligence.streamlit.app) | Python · DuckDB · LightGBM · scikit-learn · Gemini · Streamlit · Power BI |
| [**Enterprise AI Knowledge Assistant**](https://github.com/Thierry-Daconceicao-Alvares/enterprise-ai-knowledge-assistant) | RAG assistant that answers from company documents with page-level citations and declines when the answer is not there; measured on 62 labelled cases (59 passed), including prompt injection, contradictions and outdated versions | [Live demo](https://knowledge-assistant-rag.streamlit.app) | Python · Gemini · Chroma · FastAPI · Streamlit |
| [**E-commerce Analytics Engineering**](https://github.com/Thierry-Daconceicao-Alvares/ecommerce-analytics-engineering) | Layered dbt models with 74 data tests, LookML semantic layer and Looker Studio dashboard; runs locally on DuckDB, with CI | [Dashboard](https://lookerstudio.google.com/reporting/78ef8242-016f-4e9a-b9d2-32bd7bb1bd66) · [dbt docs](https://thierry-daconceicao-alvares.github.io/ecommerce-analytics-engineering/) | dbt · BigQuery · DuckDB · LookML · Looker Studio |

#### Toolbox

| | |
|---|---|
| **Data & BI** | SQL · Python · dbt · BigQuery · Power BI (DAX, Power Query) · Qlik · Looker Studio · Excel · Dataiku |
| **Automation** | Google Apps Script · JavaScript · HTML/CSS · Chart.js |
| **Machine learning & apps** | LightGBM · scikit-learn · PM4Py (process mining) · FastAPI · Next.js · ECharts |
| **Generative AI** | Multi-LLM architectures · prompt engineering · few-shot learning · use-case scoping and adoption |
| **Procurement & ERP** | SAP P2P · master data · spend analysis · supplier performance and compliance |

#### Education and certifications

- **MSc in Data & AI for Business**: machine learning, data science and generative AI, with Power BI (DAX, Power Query) and predictive modelling projects (Python, Dataiku).
- **BSc in Applied Mathematics and Computer Science for the Social Sciences (MIASHS)**, Economics track: mathematics, statistics, probability, Python and SQL.
- **Certifications**: Dataiku Machine Learning Practitioner · Dataiku Core Designer

#### Contact

[LinkedIn](https://www.linkedin.com/in/thierry-alvares/) · French (native), English (C1)
