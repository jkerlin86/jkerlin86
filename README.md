# Joseph Kerlin, PhD

Senior Data Scientist and Industrial Engineer. I build predictive models, simulation studies, and analytics tools that support operational and financial decisions.

**Background**
- PhD, Industrial and Systems Engineering, Mississippi State University
- 10+ years across automotive manufacturing, industrial engineering, and financial services analytics
- Current work: predictive modeling and decision support in automotive finance

**Core skills**
- Languages and tools: Python, SQL, Power BI, Tableau, SAS
- Methods: regression and classification modeling, forecasting, discrete-event simulation (SimPy), experimentation, model validation
- Platforms: Azure, Snowflake, Databricks

**Featured projects**
- [Charging Infrastructure as a Panel: Survival, Churn, and Coverage Optimization](https://github.com/jkerlin86/charging-infrastructure-panel) — An 11-snapshot federal panel of 171,552 charging stations, 2013 to today: about 12.7% of stations disappear from the national locator per year, and planned stations that open do so a median 686 days late. A maximal-covering optimizer, validated against brute-force optima, then matches the coverage gain of the real 5,258-station 2023-2024 build-out with 92 optimally placed stations.
- [Did Medicaid Expansion Change Coverage, and for Whom?](https://github.com/jkerlin86/medicaid-expansion-did) — A staggered difference-in-differences study of ACA Medicaid expansion on a 51-jurisdiction ACS panel, 2010-2024. Callaway & Sant'Anna group-time ATT implemented in project code and validated on a synthetic known-truth panel before use: expansion states' adult uninsurance fell 1.50 percentage points [95% CI -2.88, -0.12] relative to never-adopters, with clean pre-trends, and the crowd-out check reported honestly: private coverage share fell 2.77 points alongside the Medicaid gain.
- [Federal Supply Risk: Procurement Concentration Meets Import Dependence](https://github.com/jkerlin86/federal-supply-risk) — SQL-first screen of 84 manufacturing industries on two concentration dimensions at once: 10.8M federal contract transactions (USAspending, checked-in DuckDB SQL) against import source-country concentration from the U.S. Census Bureau trade API, cross-checked against CEPII BACI. Six industry-years flag on both dimensions at the central thresholds, and the one cell the two sources disagree on is a knife-edge documented to the third decimal.
- [Relief Radar: CFPB Complaint Outcomes x SEC Disclosure](https://github.com/jkerlin86/relief-radar) — Point-in-time modelling of monetary-relief outcomes on 19M consumer complaints, with a narrative-selection audit: only 23% of complaints carry a narrative, and they end in relief at 2.58% versus 0.73% for the rest. Includes a paired text-embedding arm and a leakage audit. The SEC EDGAR alignment component is documented in the repository and lands as a later update.
- [Shipping a Sensor Classifier That Drifts](https://github.com/jkerlin86/sensor-drift-production-ml) — Production ML under dataset drift. A gas sensor classifier that scores 99.5% under random-split validation holds only 49% under honest batch-forward evaluation; the project quantifies that gap, monitors drift, and compares retraining policies on cost. Packaged FastAPI service, tests, CI, and Docker.

**What I am building here**
A portfolio of self-contained projects in modeling, simulation, and analytics, developed on public or synthetic data. This profile will grow project by project.
