# Electric Vehicle Market Performance & Insights

An end-to-end Data Analytics, Business Intelligence, and Web Integration project analyzing global electric vehicle adoption, technical battery efficiency, total cost of ownership, and environmental sustainability across 100,000 EV data points.

---

## 📌 Project Deliverables & Live Links
- **Interactive Tableau Public Dashboard:** [View Live Dashboard](https://public.tableau.com/views/EV_Market_Performance_17931262572980/evmarketperformancedashboard)
- **Project Walkthrough Video (Google Drive):** [Watch Video Demonstration](https://drive.google.com/file/d/1geKN0tNA8n4qAxAC5mc09j8DwL3FWKDD/view?usp=drive_link)
- **Project Track:** Data Analytics with Tableau
- **Team ID:** SKILLWALLET-EV-01

---

## 🚀 Key Business Questions & Analytical Insights

1. **Global Sales Volume & Adoption:** 
   - Market adoption is heavily led by SUVs and Sedans across North America, Europe, and Asia-Pacific, capturing over 58% of the total unit volume.
2. **Range vs. Battery Capacity:** 
   - Displays a strong positive linear correlation between battery pack capacity (kWh) and driving range (km), spanning from 150 km for City Cars to over 650 km for Premium Luxury EVs.
3. **Fast Charging Dynamics:** 
   - Advanced battery chemistries (LFP, NMC, Solid-State) combined with high-capacity DC fast chargers (>150 kW) reduce 10–80% charging duration to under 25 minutes.
4. **Motor Power vs. Energy Efficiency:** 
   - Dual-motor AWD powertrains consume higher energy per km (Wh/km) but provide superior 0–100 km/h acceleration under 4.5 seconds.
5. **Economic Viability & Resale Value:** 
   - Mainstream and premium electric vehicles sustain a strong 3-year resale value retention rate (~58.5%), offsetting upfront capital investment.
6. **Insurance Cost & Safety Benchmark:** 
   - 5-star safety rating certifications significantly optimize annual insurance premiums across all vehicle weight classes.
7. **Environmental Sustainability Impact:** 
   - High-density EV replacement saves millions of metric tons of greenhouse CO2 emissions annually compared to internal combustion engines (ICE).

---

## 🛠️ Technology Stack Architecture

- **Data Processing & Analytics:** Tableau Desktop, Tableau Data Engine (.hyper Extract), Python Pandas
- **Business Intelligence & Storytelling:** Tableau Public, Tableau Storyboard (4 narrative points)
- **Web Application Backend:** Python Flask 3.1
- **Frontend Embedding:** HTML5, CSS3, Jinja2, Tableau JavaScript Embedded API
- **Version Control & Repository:** Git & GitHub

---

## 📂 Repository File Structure

```text
├── EV_Market_Performance.twb                           # Tableau Desktop Workbook file
├── app.py                                              # Flask Web Server entry point
├── templates/
│   └── index.html                                      # Embedded Tableau Dashboard HTML template
├── Project_Documentation_PDFs/
│   ├── Brainstorm_and_Idea_Prioritization.pdf          # Ideation Phase: Brainstorming & Scoring
│   ├── Define_Problem_Statements.pdf                   # Ideation Phase: Customer Persona & Statements
│   ├── Empathy_Map_Canvas.pdf                          # Ideation Phase: User Empathy Quadrants
│   ├── Project_Proposal_Proposed_Solution.pdf          # Initialization & Resource Specification
│   ├── Problem_Solution_Fit.pdf                        # Design Phase-I: 10-Element Fit Canvas
│   ├── Solution_Architecture.pdf                       # Design Phase-I: Component Layer Diagram
│   ├── Technology_Stack.pdf                            # Design Phase-II: Tech Architecture Matrix
│   ├── Solution_Requirements.pdf                       # Design Phase-II: Functional & NFRs
│   ├── Data_Flow_Diagrams_and_User_Stories.pdf         # Design Phase-II: DFD Flow & Agile Stories
│   ├── Project_Planning_Agile_Tracker.pdf              # Planning Phase: Sprints & Backlog
│   ├── Performance_Testing_Tableau.pdf                 # Performance Testing: Latency & Data Metrics
│   ├── Dashboard_Design_Report.pdf                     # Development Phase: UI Layout & Outcomes
│   ├── Story_Design_Report.pdf                         # Development Phase: Narrative Sequences
│   └── Business_Question_and_Visualisation_Report.pdf   # 9 Core Business Questions & Insights
└── README.md                                           # Comprehensive Project Overview
```

---

## 💻 Local Flask Web App Execution

To run the embedded web dashboard on your local machine:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/officialdevansh17-bot/Electric-Vehicle-Market-Performance-Insights.git
   cd Electric-Vehicle-Market-Performance-Insights
   ```

2. **Install required dependencies:**
   ```bash
   pip install flask
   ```

3. **Start the local Flask server:**
   ```bash
   python app.py
   ```

4. **Access the application:**
   Open your browser and navigate to:
   ```text
   http://127.0.0.1:5000/
   ```

---

## 👨‍💻 Author
- **Devansh Sharma**
- Project developed for **Tableau Data Analytics Capstone Certification** (SkillWallet Platform)
