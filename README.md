<h1 align="center">🏥 Hospital Patient Analysis Dashboard (Excel)</h1>
<p align="center"><i>Integrated view of patient demographics, treatments, costs, readmissions, and satisfaction</i></p>

---

<h2>📊 Project Overview</h2>
<p>
  The <strong>Hospital Patient Analysis Dashboard</strong> is a visual analytics project implemented in <strong>Microsoft Excel</strong>, designed to aggregate and visualize hospital data (patients, treatments, costs, readmissions, satisfaction).  
  It aims to give hospital administrators, clinicians, and management a centralized, interactive, and accessible tool to monitor key metrics — enabling data-driven decisions around cost management, resource allocation, and quality of care.  
</p>

---

<h2>🎯 Purpose</h2>
<p>
  This dashboard helps hospital staff make informed decisions by:  
  <ul>
    <li>Consolidating patient, treatment, cost, readmission, and satisfaction data in a single workbook</li>
    <li>Visualizing demographic distributions (e.g., gender breakdown), overall patient counts, and cost totals</li>
    <li>Highlighting cost drivers by treatment type (treatment-wise cost breakdown)</li>
    <li>Displaying outcome and patient-experience metrics (readmissions, satisfaction scores)</li>
    <li>Providing slicing/filtering capabilities (e.g., by gender, readmission status, cost range, satisfaction) to support drill-downs and sub-group analysis</li>
    <li>Supporting regular reporting and monitoring (monthly/quarterly or as needed) without requiring expensive BI tools</li>
  </ul>
</p>

---

<h2>🛠️ Tools & Technologies</h2>
<ul>
  <li><strong>Microsoft Excel</strong> – for data storage, aggregation (via formulas or PivotTables), and visualizations (charts, graphs, dashboards)</li>
  <li><strong>Structured data sheets</strong> – organized raw data sheets for patients, treatments, costs, satisfaction/readmission</li>
  <li><strong>Aggregated / helper sheets</strong> – for computed KPIs, summaries, and supporting data for charts</li>
</ul>

---

<h2>📁 Dashboard Components</h2>
<p>The dashboard includes the following components (tabs/sections in Excel):</p>

<h3>✅ Summary KPI Cards</h3>
<ul>
  <li>Total number of patients</li>
  <li>Total number of male (and female) patients</li>
  <li>Total cost incurred (overall/maybe per period)</li>
</ul>

<h3>👥 Demographic & Satisfaction Overview</h3>
<ul>
  <li>Gender-wise breakdown (bar/pie chart) — showing distribution of patients by gender</li>
  <li>Satisfaction score distribution — donut/pie chart showing counts of patients by satisfaction levels</li>
  <li>Possibility to filter by gender to compare satisfaction across demographics</li>
</ul>

<h3>🏥 Treatment & Cost Analysis</h3>
<ul>
  <li>Treatment-wise total cost breakdown (bar chart) — shows which treatments contribute most to cost</li>
  <li>Treatment counts or utilization (if available) — number of treatments performed per category</li>
  <li>Ability to cross-filter with cost, satisfaction, or readmission status to analyze correlations (e.g., high-cost treatments vs. readmissions/satisfaction)</li>
</ul>

<h3>📈 Readmission & Outcome Metrics</h3>
<ul>
  <li>Readmission status summary (counts or percentages of readmitted vs non-readmitted patients)</li>
  <li>Cross-analysis with satisfaction (e.g., are readmitted patients more or less satisfied) or with cost/treatment types</li>
</ul>

<h3>🔎 Interactive Filters / Slicers</h3>
<ul>
  <li>Simple filters or drop-downs for gender, readmission status, treatment type, cost ranges, satisfaction scores</li>
  <li>Allows users to dynamically narrow down data subsets — useful for focused analysis (e.g., costliest treatments, dissatisfied patients, readmission cases)</li>
</ul>

---

<h2>📌 Key Insights (What the Dashboard Can Reveal)</h2>
<ul>
  <li>A clear picture of hospital patient demographics and volume (how many patients, gender distribution)</li>
  <li>Which treatments are driving the most cost, allowing administrators to identify cost-intensive services and explore efficiencies</li>
  <li>Patterns between treatment types, cost, satisfaction, and readmissions — potentially highlighting areas needing quality improvement or cost control</li>
  <li>Distribution of patient satisfaction across demographics — useful for identifying groups requiring improved patient-experience interventions</li>
  <li>Overall cost burden — total cost metric supports budgeting, financial reporting, and resource allocation</li>
  <li>Ability to drill down and segment data flexibly — enabling granular insights rather than just aggregated overviews</li>
</ul>

---

<h2>🔍 How to Use the Dashboard</h2>
<ol>
  <li>Open the Excel workbook (e.g., <code>Hospital_Patient_Analysis.xlsx</code>).</li>
  <li>Navigate to the raw data input sheets (“Patients_Data”, “Treatments_Data”, “Costs_Data”, “Satisfaction_Readmission_Data”) and add or update records as needed.</li>
  <li>If using data import or preprocessing (Power Query, macros), run the refresh routines to update aggregated data.</li>
  <li>Go to the “Dashboard” sheet to view summary KPIs and visualizations.</li>
  <li>Use filters/slicers or drop-downs to drill down by gender, treatment type, readmission status, cost range, or satisfaction score.</li>
  <li>Interpret charts to understand cost drivers, patient distribution, readmissions, satisfaction, and derive actionable insights for management, cost control, or quality improvement.</li>
  <li>For periodic reporting (monthly/quarterly), after data updates — review the dashboard to monitor changes over time, track trends, and communicate results to stakeholders.</li>
</ol>

---

<h2>👥 Target Users / Audience</h2>
<ul>
  <li>Hospital administrators and management — for cost monitoring, budgeting, resource planning</li>
  <li>Clinical leads and department heads — to understand treatment distribution, readmissions, satisfaction across patient demographics</li>
  <li>Quality-assurance / patient-experience teams — to analyze satisfaction patterns and link with treatments/readmissions</li>
  <li>Finance teams — to monitor overall cost burden and identify cost-intensive treatments</li>
  <li>Hospital staff responsible for reporting — to generate regular summaries and track key metrics over time</li>
</ul>

---

<h2>📂 Project Workbook Structure (Excel Layout)</h2>
<pre>
📦 Hospital_Patient_Analysis/
├── README.html / Documentation (this file)  
├── Patients_Data            # Raw patient records (demographics, basic info)  
├── Treatments_Data          # Raw treatment details per patient (treatment type, dates, etc.)  
├── Costs_Data               # Raw cost/billing/expenditure records  
├── Satisfaction_Readmission_Data  # Patient feedback, satisfaction scores, readmission status  
├── Aggregated_Data / Pivot_Data   # Helper sheets with aggregated values, computed KPIs  
├── Dashboard                # Main dashboard sheet with KPIs, charts, slicers  
└── (Optional) Configuration  # Lookup tables (e.g., treatment codes), drop-down lists, data validation  
</pre>

---

<h2>✅ Conclusion</h2>
<p>
  The Excel-based <strong>Hospital Patient Analysis Dashboard</strong> is a practical and cost-effective solution for small to medium-sized hospitals or clinics that need consolidated, visual, and interactive reporting of patient, treatment, cost, satisfaction, and readmission data.  
  With a well-structured workbook and a disciplined data entry/update process, stakeholders can monitor hospital performance, identify cost drivers, analyze patient outcomes and satisfaction, and support data-driven management decisions — all without requiring a heavy BI infrastructure.  
</p>
