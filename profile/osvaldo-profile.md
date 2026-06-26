# Osvaldo Ruiz — Candidate Profile
# Last updated: June 2026
#
# HOW TO UPDATE THIS FILE
# ========================
# When you complete a new project, add it under PROJECTS following the existing format.
# Then update the SKILLS MATRIX section -- add any new tools/technologies to the right category.
# Each skill entry should map to at least one project so it can be evidenced in applications.
# Update CURRENT ROLES when your employment changes.
# Do not change the section headers -- the skill uses them to parse this file.

## METADATA
Last profile update: 2026-06-25
Last resume generated: never

---

## IDENTITY

Name: Osvaldo Ruiz
Location: San Diego / Tijuana (cross-border)
Target Roles: Operations Analyst, Business Analyst, Data Analyst
LinkedIn: https://linkedin.com/in/osvaldoruiz
GitHub: https://github.com/ruizosvaldo
Portfolio: https://www.osvaldoruiz.com/projects/

---

## CURRENT ROLES

**Data Analyst (Volunteer)** | Human Health Project (HHP) | 2026 - Present
- Working across programme outcomes data, CRM data (EspoCRM), and SPI data streams
- Onboarding contact: Adaeze Nwachukwu

**Program Manager** | The LEAGUE of Amazing Programmers | Ongoing
- Nonprofit coding education organization serving K-12 students
- Built full-stack student progress reporting platform (see LEAGUE Report project)
- Developed AP Computer Science A curriculum, MakeCode Arcade tutorials
- Created instructor accountability and parent reporting documents

**Programs Coordinator** | Border Angels | Ongoing
- Humanitarian nonprofit supporting migrants along the U.S.-Mexico border
- Built organization-wide ETL pipeline and Google Sheets dashboard covering 13+ programs
- Produced partnership waivers, intake forms, event reports, and volunteer recruitment materials

---

## EDUCATION

Information Systems (undergraduate background)

**Completed Coursework:**
- COMP 643: DevOps (Debian VMs, SSH, DNS, DHCP, Apache, Docker, Ansible)
- Linux Server Side Development (in progress)

---

## PROJECTS
# Format: Project Name | Technologies | Year | Link (if public)
# Under each project, list what it demonstrates for operations/analyst roles.

**LEAGUE Report: Student Progress Report Application** | TypeScript, React, Node.js, SQLite, Claude AI API, Pike13 API, GitHub API, Drizzle ORM | 2025-2026
- Synced student roster and scheduling data from Pike13 REST API into a normalized SQLite database
- Integrated GitHub API to fetch per-student commit history; fed activity data into Claude AI API to auto-generate monthly progress reviews
- Built admin compliance grid tracking review submission status across all instructors and reporting periods
- Implemented instructor dashboard with monthly stats: roster size, review counts, TA check-in logs
- Collected guardian feedback via unauthenticated public links embedded in outbound emails for longitudinal satisfaction tracking
- Automated monthly Slack reminders via cron-scheduled bot querying pending review counts
- Demonstrates: workflow automation, cross-system data integration, stakeholder reporting, compliance tracking

**MLB Scout: Game Preview Analytics** | Python, Streamlit, REST APIs, Statcast, pybaseball, Plotly, Pandas | 2025-2026
- Live at: https://mlbscout.streamlit.app/
- Ingests real-time data from four sources (MLB Stats API, ESPN, Baseball Savant, FanGraphs), consolidating 10+ endpoints
- Designed disk-backed caching layer (Parquet + JSON) with per-key TTLs to minimize redundant API calls
- Engineered batter matchup scoring model blending xwOBA, K%, barrel rate, platoon advantage into normalized 1-10 signal
- Visualized spray charts and exit-velocity heat maps using Plotly and Statcast coordinate transforms
- Demonstrates: multi-source data ingestion, scoring model design, performance dashboard development

**Las Vegas Raiders: 2026 Scheme Fit Analysis** | Python, Streamlit, scikit-learn, nfl_data_py, DuckDB, Plotly, Pandas | 2026
- Live at: https://raiders.streamlit.app/
- Built ETL-to-dashboard pipeline ingesting NFL play-by-play data and constructing snap-weighted position archetypes
- Engineered dual scoring dimensions (Physical Fit, Statistical Similarity) using Euclidean distance converted to 0-100 grade scale
- Applied experience-aware grading logic for rookies, sophomores, and veterans
- Cached pipeline outputs to DuckDB; deployed to Streamlit Cloud via pre-exported CSVs
- Demonstrates: ETL pipeline design, scoring model engineering, operational deployment

**Border Angels EOY Programs Dashboard** | Python, Pandas, Google Cloud Console, Google Sheets API | 2024-2025
- Built organization-wide reporting dashboard consolidating annual program data for 13+ programs
- Developed Python ETL pipeline to extract, clean, and transform raw program data from multiple departments
- Automated data loading through Google Cloud Console, enabling monthly refresh cycles
- Consolidated KPIs: 27+ community events, 84+ unique volunteers, $84,405+ in program expenditures, 1,362+ people served
- Demonstrates: ETL automation, nonprofit operations reporting, stakeholder data consolidation, process improvement

**Google Analytics E-Commerce Dashboard** | BigQuery SQL, Google Sheets, Connected Sheets, Pivot Tables | 2025
- Live at: https://docs.google.com/spreadsheets/d/1a7nwZZNt5kNAkdBu2Ezm4Io1LKBuuTjDrpUF3jHWhvA/
- Analyzed 903,653 sessions and $1.54M revenue using BigQuery SQL views with UNNEST operations
- Built interactive dashboard with 4 pivot tables and 6 slicers for real-time filtering
- Identified mobile optimization opportunity: desktop generates 95.6% of revenue while mobile drives 23% of traffic
- Demonstrates: SQL analytics, self-service BI tooling, business insight generation

**Economic Indicators Analytics Dashboard** | Python, Pandas, SQL, FRED API, PostgreSQL, Google Sheets API | 2024-2025
- Automated data extraction from Federal Reserve API for GDP, unemployment, inflation, and interest rate indicators
- Designed normalized PostgreSQL database schema for efficient storage and querying
- Integrated Google Cloud APIs for automated reporting to Google Sheets
- Demonstrates: API integration, database design, automated reporting pipelines

**HR Attrition Analysis Dashboard** | Tableau, Public Data, HR Analytics | 2025
- Live at: https://public.tableau.com/views/IBM_Attrition_17710459255670/HRAttritionAnalysis
- Analyzed 1,470-employee IBM HR dataset to identify key drivers of employee turnover
- Built calculated fields for attrition rate, tenure buckets, salary bands, and satisfaction categories
- Identified: Sales Representatives have 40% attrition (3x company average); overtime workers leave at 30% vs 10%
- Demonstrates: workforce analytics, executive dashboard design, pattern identification

**US Housing Market Analysis Dashboard** | Tableau, US Census Data | 2025
- Live at: https://public.tableau.com/app/profile/osvaldo.ruiz3189/viz/U_S_HomeSales1963-2016/Dashboard
- Analyzed 53 years of US Census data (1963-2016) with regional filtering, price trend analysis, inventory insights
- Demonstrates: long-horizon trend analysis, interactive dashboard design

**Customer Churn Analysis** | Python, Pandas, Scikit-learn, Seaborn, Streamlit | 2024-2025
- Live at: https://oruiz-ccd.streamlit.app
- Built ML dashboard identifying key churn factors in telecom dataset using Random Forest
- Identified top 10 features contributing to churn; displayed classification report and confusion matrix
- Demonstrates: machine learning application, churn/retention analysis

**CardScout** | Python, SQLite, eBay API, COMC API, APScheduler, Gmail SMTP | 2025
- Sports card arbitrage app with automated price monitoring and Gmail alert system
- Production eBay credentials secured; scheduled price checks via APScheduler
- Demonstrates: API integration, automated alerting, arbitrage logic

**Job Hunter Automation** | Python, Claude API, Playwright, Gmail SMTP, SQLite, APScheduler | 2025
- Automated job application pipeline: python-jobspy scraping, Claude API scoring, Playwright auto-apply
- Custom scrapers planned for USAJobs, County of San Diego, City of San Diego, CalCareers
- Demonstrates: workflow automation, RPA-style tooling, end-to-end pipeline design

---

## SKILLS MATRIX
# HOW TO UPDATE: When you add a project above, add any new tools here under the right category.
# Format: Tool/Technology (evidenced by: Project Name)

### Data & Analytics
- Python (evidenced by: Border Angels Dashboard, Economic Indicators, Customer Churn, MLB Scout, Raiders, CardScout)
- SQL / BigQuery (evidenced by: Google Analytics Dashboard, Economic Indicators)
- PostgreSQL (evidenced by: Economic Indicators)
- DuckDB (evidenced by: Raiders Scheme Fit)
- SQLite (evidenced by: LEAGUE Report, CardScout, Job Hunter)
- Pandas (evidenced by: Border Angels Dashboard, Economic Indicators, MLB Scout, Customer Churn)
- NumPy (evidenced by: Customer Churn)

### Machine Learning & Modeling
- Scikit-learn (evidenced by: Customer Churn, Raiders Scheme Fit)
- Random Forest (evidenced by: Customer Churn)
- Euclidean distance / scoring model design (evidenced by: Raiders Scheme Fit)
- Weighted multi-factor regression logic (evidenced by: MLB Scout)

### Visualization & BI
- Tableau (evidenced by: HR Attrition, US Housing Market)
- Plotly (evidenced by: MLB Scout, Raiders Scheme Fit)
- Streamlit (evidenced by: MLB Scout, Raiders Scheme Fit, Customer Churn, Sales Insights)
- Matplotlib / Seaborn (evidenced by: Customer Churn)
- Google Sheets dashboards (evidenced by: Border Angels Dashboard, Economic Indicators)

### Engineering & Infrastructure
- Google Cloud Platform / GCP (evidenced by: Border Angels Dashboard, Economic Indicators)
- Google Apps Script (evidenced by: Border Angels pipeline)
- Docker (coursework: COMP 643)
- Ansible (coursework: COMP 643)
- Playwright (evidenced by: Job Hunter)
- APScheduler (evidenced by: CardScout, Job Hunter)

### APIs & Integrations
- REST APIs (evidenced by: LEAGUE Report, MLB Scout, Economic Indicators, CardScout)
- Pike13 API (evidenced by: LEAGUE Report)
- GitHub API (evidenced by: LEAGUE Report)
- Claude AI API (evidenced by: LEAGUE Report, Job Hunter)
- FRED API (evidenced by: Economic Indicators)
- Google Sheets API (evidenced by: Border Angels Dashboard, Economic Indicators)
- eBay API / COMC API (evidenced by: CardScout)
- Slack API (evidenced by: LEAGUE Report)

### Web & Full-Stack
- TypeScript (evidenced by: LEAGUE Report)
- React (evidenced by: LEAGUE Report)
- Node.js (evidenced by: LEAGUE Report)
- Drizzle ORM (evidenced by: LEAGUE Report)

### Operations & Program Management
- 9+ years nonprofit program management (The LEAGUE, Border Angels)
- Cross-departmental data coordination (evidenced by: Border Angels Dashboard)
- Compliance tracking systems (evidenced by: LEAGUE Report)
- Stakeholder reporting (evidenced by: Border Angels Dashboard, LEAGUE Report)
- Volunteer and event coordination (evidenced by: Border Angels)
- K-12 curriculum development (evidenced by: The LEAGUE)
- EspoCRM (evidenced by: HHP volunteer role)

---

## STATE GOVERNMENT EXPERIENCE

- Applied for Caltrans AGPA (Associate Governmental Program Analyst) role; completed salary negotiation
- Prepared for EDD AGPA interview
- Prepared for UCSD analyst interview
- Familiar with California state application requirements, SOQ format, and AGPA-level job classification

---

## ADDITIONAL CONTEXT FOR APPLICATIONS

- Cross-border professional with strong ties to San Diego and Tijuana communities
- Experience supporting vulnerable populations (migrants, underserved youth)
- Freelance technical work: City Boxing (Weebly contact form fix), texcpe.com (PHP/SQLite site with Stripe planning)
- Freelance rate: $125/hour
- Languages: English, Spanish (implied by cross-border work and Border Angels role)
