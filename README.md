# Vendor Performance Analysis using Python and Power BI


This project provides an end-to-end analysis of **vendor performance** based on sales data.  
It covers the entire pipeline — from **data ingestion and cleaning** to **exploratory analysis, automation of summary reports, and dashboard development** using Power BI.  

The final deliverables include:  
- Automated **vendor performance summaries**  
- Interactive **Power BI dashboard**  
- Professional **PDF report** with actionable insights  


## 📂 Project Structure
```
├── data/
│   └── vendor_sales_summary.csv
├── notebooks/
│   ├── Exploratory Data Analysis.ipynb
│   └── Vendor Performance Analysis.ipynb
├── scripts/
│   ├── get_vendor_summary.py
│   └── ingestion_db.py
├── dashboard/
│   └── vendor_performance.pbix
├── reports/
│   └── Vendor Performance Report.pdf
└── README.md
```

## 🛠️ Tech Stack
- **Languages**: Python (Pandas, Matplotlib, Seaborn)
- **Tools**: Jupyter Notebook, Power BI, Excel
- **Other**: PDF Reporting

## 💡 Key Features
- Automated ingestion and cleaning of vendor sales data
- Detailed Exploratory Data Analysis (EDA) to identify trends and patterns
- Python scripts for automated vendor summary reports
- Interactive and visually rich dashboard built using Power BI
- Finalized insights compiled in a professional PDF report

🚀 ## How to Run

1.  **Clone the Repository**:
    ```sh
    git clone <your-repository-url>
    ```
2.  **Install Dependencies**:
    ```sh
    pip install pandas matplotlib seaborn jupyter
    ```
3.  **Run Analysis Notebooks**: Navigate to the `/notebooks` directory and open the Jupyter Notebooks to view the data exploration and analysis steps.
    ```sh
    cd notebooks/
    jupyter notebook "Exploratory Data Analysis.ipynb"
    ```
4.  **Generate Vendor Summary**: Use the `get_vendor_summary.py` script to generate a summary report from the raw data.
    ```sh
    python scripts/get_vendor_summary.py
    ```
5.  **View Dashboard**: Open the `vendor_performance.pbix` file in the `/dashboard` directory using Power BI Desktop to interact with the dashboard.
6.  **Review Final Report**: The final analysis and insights are available in the `Vendor Performance Report.pdf` located in the `/reports` directory.

---

📈 ## Outputs

-   **Vendor Performance Summary CSV**: A clean, summarized CSV file located in the `data/` directory.
-   **Power BI Dashboard**: An interactive `.pbix` file providing a comprehensive visual analysis.
-   **Final Insights PDF Report**: A detailed report outlining the key findings and business recommendations.

