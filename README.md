 🗺️ Geological Hazard Zone Assessment with Synthetic Data

This project generates synthetic geological data for hazard zone classification and exports it as an Excel file. The dataset simulates key environmental and geophysical variables to help prototype models for risk analysis, landslide prediction, or terrain classification.

---

## 📦 Project Structure

├── synthetic_geological_hazard_data.xlsx # Exported dataset ├── generate_hazard_data.py # Python script for data generation └── README.md # Project documentation

yaml
Copy
Edit

---

## 🧪 Features of the Dataset

Each record includes:

- `slope`: Terrain slope in degrees (0–60)
- `lithology`: Encoded rock type (0 = sedimentary, 1 = igneous, 2 = metamorphic)
- `rainfall`: Annual rainfall in mm (500–3000)
- `fault_distance`: Distance to nearest fault line in km (0–50)
- `vegetation`: Vegetation index (0–1)
- `hazard_class`: Risk classification (`Low`, `Medium`, `High`)

---

## ⚙️ How to Generate Data

### Prerequisites

```bash
pip install numpy pandas openpyxl
Run Script
bash
Copy
Edit
python generate_hazard_data.py
This will:

Generate synthetic samples (default = 3000)

Save the dataset to synthetic_geological_hazard_data.xlsx

🧠 Use Cases
Testing ensemble machine learning models

Simulating geological risk for academic studies

Creating demos for geospatial AI

Visualizing hazard maps

📂 Output Example

slope	lithology	rainfall	fault_distance	vegetation	hazard_class
25.3	0	1800.4	10.5	0.76	Medium


Author
Tarinabo williamtarinabo@gmail.com
