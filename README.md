# STERLING-HEIGHTS-DATA-ANALYSIS : Built an Interactive Dashboard using Power BI that will help the company's management make proactive decisions.

![premium_photo-1682130157004-057c137d96d5](https://github.com/user-attachments/assets/b2efd8d1-caeb-4fdc-bd7d-ede669376ecc)



## Table of Content

- [Description](#description)
- [Business Introduction](#business-introduction)
- [Business Problem](#business-problem)
- [Rationale for the Project](#rationale-for-the-project)
- [Processes](#processes)
- [Insights](#insights)
- [Recommendations](#recommendations)

### **DESCRIPTION**
The project offered an opportunity to design end to end data analytics solutions using Power BI to create a centralized dashboard that could track patient flow, doctor availability and satisfaction metrics in real time to make proactive decisions.

<img width="1432" height="807" alt="Screenshot 2025-07-29 181832" src="https://github.com/user-attachments/assets/11009668-500f-4175-bb7d-bd8bda46b0d6" />
<img width="1425" height="806" alt="Screenshot 2025-07-29 181904" src="https://github.com/user-attachments/assets/0567c150-e586-4f01-9017-acd17549bd13" />
<img width="1436" height="802" alt="Screenshot 2025-07-29 181935" src="https://github.com/user-attachments/assets/9c4767f3-231d-481e-977b-f831430d6b7a" />

### **BUSINESS INTRODUCTION**
Sterling Heights Hospital, a mid-sized healthcare facility, is facing growing challenges in delivering efficient and patient-centered care. The hospital is struggling with operational inefficiences such as prolonged patient wait times, uneven doctor workloads, and poorly tracked admission patterns, all of which contributed to declining patient satisfaction.

### **BUSINESS PROBLEM**
- Lack of Visibility into Visit Patterns and Operational inefficiencies.
- Long patient wait times.
- Imbalance in doctor to patient ratio.

### **Rationale for the Project**
- Enhance Patient Experience.
- Service Quality Monitoring.
- Resource Allocation.

### **Rationale for the Project**
- Data Preparation.
- Data Normalisation and Modelling.
- Creation of Measures and Data Table Generation.
- Dashboard Development.
- Insights.
- Recommendations.

### **PROCESSES**
### Step 1: Data Preparation
Tools: Power Query(Power BI)
- Removed duplicates and blanks.
- Standardized data formats(Date, Doctor's name)
- Created Conditional Column from key metrics (e.g. Admission, Patient Age group)
- Created Calculated Column(e.g age, total years, start of hour) 
- Created Fact Tables and Dimension Tables from main data table

### Step 2: Data Normalization and Modelling.
Tools: Power BI Data Model, DAX
- Defined relationships between tables (e.g., Doctors Table, Patients Table, Sterling Height Fact Table, Location Table, Treatment Table)
- Created Measures using Dax for key KPIs like No. of Visits, No. of Patients, Total Profit, Average Wait Time, Admission Rate, No of Doctors, Doctor to Patient Ratio and so on).
- Created Date Table to extract Year, Month , Month name, Week, Weekday.

### Step 3: Analysis and Dashboard Creation.
Tools: Power BI Visualization Features.
- Built interactive dashboards with Filters, Slicers and drill through functionality.
- Used line charts, Area charts, Bar charts, Scatter Charts, Matrix, Tables, Donut Charts to visualize metrics and show trends.

### **INSIGHTS AND RECOMMENDATIONS**
### Insights
- Current Average Wait times was 92 minutes with moderate satisfaction of (3.02).
- Doctore Availability flunctuated fropping to 18 on Day 22
- Radiology, Orthopedics and Dermatology has the highest patients visits while Pediatics and Dentistry had the lowest Patient visits
- 59% of visits are non-admitted, highlighting strong outpatient usuage.
- Majority of the hospital visits were made by Male Patients.
- A detailed table of Patients capturinng Patient Name, Satisfaction Score, Treatment type, wait time etc.

### Recommendations
- Implement a fast track system for kow complexity cases.
- Explore digital check ins or queue management tools.
- Redesign appointment scheduling process to reduce bottlenecks during peak hours.
- Use Patient visit trend to align staffing with demands by department and times taking into consideration peak periods.
- Marketing and advertisement to create awareness for departments with lesser number of patients and discounts to attract patients.
- Survey to be carried out amongst customers to find out how services can be improved.
- Maintan and routinely review the Patient register Dashboards for constant follow up on Customers that stopped visiting.
- Introduce online consultations or follow ups to reduce physical appearance.


