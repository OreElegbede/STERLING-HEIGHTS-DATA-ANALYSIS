# STERLING-HEIGHTS-DATA-ANALYSIS : Built an Interactive Dashboard using Power BI that will help the company's management make proactive decisions.
## Table of Content

- [Description](#description)
- [Business Introduction](#business-introduction)
- [Business Problem](#business-problem)
- [Rationale for the Project](#rationale-for-the-project)
- [Processes](#processes)
- [Insights](#insights)
- [Recommendations](#recommendations)

### **DESCRIPTION**
The project offered an opportunity to design end to end data analytics solutions using Power BI to create a centralized dashboard that could track patient flow, doctor availability and satifaction metrics in real time to make proactive decisions.

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
- July has the highest number of Patients visiting the Hospital basedon 5 years analysis
- Most piatents visit the hospital on Fridays.
- Female Patients have the highest number of visits.
- The hospital had fewer doctors in some specialty like Dentistry which led to increase in wait times for Patients.
- Wait times for Female Patients were more than wait times for Male Patients.
- Some doctors were less busy than other doctors.

### Recommendations
- More dentists need to be hired to cover for the number of patients that visit the hospital for dental treatment. This should extend to other specialities with fewer patients. Other specaility doctors should       also be considered to reduce Doctors being over-worked
- Doctors should be allocated for Female Patients to reduce their wait times.
- A survey to be carried out amongst patience to determine how to improve the satisfaction rate.
- Patients with decline in number of visits should be contacted to follow up with them and find out why there is a decrease in visits.
- Incentives should be implemented for doctors who frequent and attend to more patience to encourage others.
- More doctors should be made available for months like July with high number of patients visits.


