🗺️ **Geological Hazard Zone Assessment with Synthetic Data**

This project generates synthetic geological data for hazard zone classification and exports it as an Excel file.
The dataset simulates key environmental and geophysical variables to help prototype models for risk analysis, landslide prediction, and terrain classification.

📦 Project Structure


├── synthetic_geological_hazard_data.xlsx   # Exported synthetic dataset
├── generate_hazard_data.py                 # Python script for data generation
└── README.md                               # Project documentation


🧪 **Features of the Dataset**

Each generated record includes:
slope: Terrain slope in degrees (0–60)

lithology: Encoded rock type
(0 = sedimentary, 1 = igneous, 2 = metamorphic)

rainfall: Annual rainfall in millimeters (500–3000 mm)

fault_distance: Distance to the nearest fault line (0–50 km)

vegetation: Normalized vegetation index (0–1)

hazard_class: Risk classification (Low, Medium, High)

⚙️ **How to Generate Data**


📋 Prerequisites

Install required Python libraries:

pip install numpy pandas openpyxl

▶️ Run the Script

Generate the dataset by running:

python generate_hazard_data.py

This will:

Create synthetic samples (default = 3000 samples)

Save the dataset to synthetic_geological_hazard_data.xlsx

🧠 Use Cases
Testing ensemble machine learning models (Random Forest, XGBoost, etc.)

Simulating geological risk for academic and industry research

Creating geospatial AI demos for hazard prediction

Visualizing hazard maps in tools like QGIS, ArcGIS, or Python visualization libraries

📂 Output Example

slope	lithology	rainfall	fault_distance	vegetation	hazard_class
25.3	0	1800.4	10.5	0.76	Medium
47.2	2	2750.9	3.4	0.34	High
13.8	1	950.7	22.1	0.89	Low



✍️ Author
Tarinabo  williamtarinabo@gmail.com
