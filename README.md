# Healthcare Operations Dashboard  
### Data-Driven Intelligence for Healthcare Performance Optimization  

Live Application  
https://healthcare-operations-dashboard.streamlit.app/

---

## 1. Overview  

The Healthcare Operations Dashboard is a multi-page analytical web application developed using Streamlit. It transforms structured healthcare data into actionable operational insights that support performance monitoring, clinical intelligence, capacity planning, and workforce optimization.

This project demonstrates applied data analytics, KPI modeling, modular dashboard engineering, and healthcare operations intelligence within a simulated hospital environment.

---

## 2. Objectives  

The dashboard was designed to enable healthcare stakeholders to:

- Monitor critical operational KPIs in real time  
- Analyze patient demographics and demand trends  
- Track clinical and disease patterns  
- Evaluate hospital capacity utilization  
- Support staffing and workforce planning decisions  
- Improve operational visibility through interactive analytics  

---

## 3. Core Features  

### Executive Overview  
- Real-time KPI summaries  
- Operational performance indicators  
- Executive-level performance visibility  

### Patient Demographics and Demand Analytics  
- Demographic segmentation  
- Admission trend analysis  
- Department-level demand insights  

### Clinical and Disease Intelligence  
- Diagnosis frequency tracking  
- Disease distribution analysis  
- Clinical trend visualization  

### Operational Efficiency and Capacity Tracking  
- Bed occupancy monitoring  
- Capacity utilization metrics  
- Resource allocation insights  

### Staffing and Resource Optimization  
- Workforce demand analysis  
- Staffing efficiency indicators  
- Resource planning support  

### Advanced Functionality  
- Global filtering (date range, department, demographics)  
- Multi-page modular navigation  
- Performance optimization using Streamlit caching  
- Patient journey timeline visualization  
- Capacity planning simulation tool  
- Exportable dashboard views  

---

## 4. Technology Stack  

- Python  
- Streamlit  
- Pandas
- Numpy
- Matplotlib
- Plotly  
- Seaborn
- ReportLab
- Excel-based dataset integration

---

## 5. Repository Structure  

```
Healthcare-Operations-Dashboard/
│
├── app.py
├── requirements.txt
├── .gitignore
├── README.md
│
├── .streamlit/
│   └── config.toml
│
├── data/
│   └── dataFinal.xlsx
│
├── myPages/
│   ├── __init__.py
│   ├── data_loader.py
│   ├── page1.py
│   ├── page2.py
│   ├── page3.py
│   ├── page4.py
│   ├── page5.py
│   └── page6.py
│
└── Agile_document/
    ├── Eekshita_agile_document.xls
    ├── G2_Defence_Tracker.xlsx
    └── G2_Unit_testplan.xlsx
```

---

## 6. Running the Application Locally  

### Install Dependencies  

```
pip install -r requirements.txt
```

### Run the Dashboard  

```
streamlit run app.py
```

The application will launch at:  
http://localhost:8501

---

## 7. Dataset  

Primary dataset:  
`data/dataFinal.xlsx`

The dataset must remain inside the `data/` directory for successful execution.

---

## 8. Development Methodology  

This project was developed following Agile practices, including:

- Product backlog planning  
- Sprint-based development cycles  
- Iterative feature enhancement  
- Structured documentation and tracking  

All Agile documentation is available in the `Agile_document/` directory.

---

## 9. Skills Demonstrated  

- Healthcare Operations Analytics  
- KPI Modeling and Performance Measurement  
- Modular Multi-Page Dashboard Architecture  
- Data Visualization and Insight Communication  
- Performance Optimization Techniques  
- Applied Agile Project Execution  
