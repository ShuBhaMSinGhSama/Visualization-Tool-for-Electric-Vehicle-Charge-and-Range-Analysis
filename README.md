DashBoard Link: https://public.tableau.com/views/EV_Charge_Range_Analysisfinal/EVPerformanceDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Story Link: https://public.tableau.com/views/EV_Charge_Range_Analysisfinal/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

⚡ Visualization Tool for Electric Vehicle Charge and Range Analysis
An end-to-end Data Analytics web application that provides deep insights into the Electric Vehicle (EV) ecosystem. This project integrates a robust MySQL backend, high-fidelity Tableau visualizations, and a modern Flask web interface to analyze EV performance, market trends, and charging infrastructure.

🚀 Live Dashboards
Interactive Analysis Portal: EV Performance Dashboard

The EV Story (India Focus): Story of Electric Cars in India

🛠️ Tech Stack
Frontend: HTML5, CSS3 (Glassmorphism UI), JavaScript

Backend: Python (Flask)

Database: MySQL Workbench (Data Storage & Querying)

Visualization: Tableau Desktop & Tableau Public

Environment: VS Code, Virtualenv

📊 Project Architecture
The project follows a structured data pipeline:

Data Acquisition: Sourced multiple datasets including ElectricCarData_clean, EVIndia_clean, and ElectricVehicleChargingStation_clean.

Database Engineering: Created the ev_project database in MySQL. Performed data cleaning and structured queries to prepare the data for visualization.

Visualization: Connected Tableau to the processed data to build three primary dashboards and one comprehensive Storyboard.

Web Integration: Developed a professional Flask application with a sidebar-navigation UI to host the embedded Tableau visualizations seamlessly.

📈 Key Insights & Dashboards
1. Global EV Market Analysis
Performance Metrics: Analysis of Top Speed, Efficiency, and PowerTrain types by brand.

Market Composition: Breakdown of models by Body Style and Brand.

2. India EV Market Analysis
Price vs. Range: A scatter plot analysis determining the value proposition of EVs in the Indian market.

Range Analysis: Detailed tracking of mileage/range across available Indian models.

3. Charging Infrastructure (India)
Geographic Mapping: A map-based visualization of charging stations across India.

Distribution: Treemaps and Donut charts showing power distribution and service types.

💻 Installation & Setup
Clone the repository

Bash
git clone https://github.com/your-username/ev-analysis-tool.git
cd ev-analysis-tool
Set up a Virtual Environment

Bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install Dependencies

Bash
pip install flask
Run the Application

Bash
python app.py
Access the tool at http://127.0.0.1:5000/.

📂 Repository Structure
Plaintext
├── app.py              # Flask Backend
├── static/
│   └── css/
│       └── style.css   # Custom Professional UI Styling
├── templates/
│   └── index.html      # Main Dashboard Page (Tabbed Interface)
└── data/               # (Optional) CSV datasets used for Tableau

👤 Author
Shubham Singh


