# ANPR and ATCC for Smart Traffic Management

Welcome to the GitHub repository for our innovative **Smart Traffic Management System**! This project integrates **Automatic Number Plate Recognition (ANPR)** and **Automatic Traffic Classification and Control (ATCC)** to revolutionize urban mobility in smart cities. By employing advanced **Deep Learning** and **Object Detection** techniques, the system ensures efficient traffic flow, reduces congestion, and enhances road safety.

---

## 🎯 Project Overview
This project aims to:
- Automate traffic monitoring using ANPR and ATCC.
- Provide data-driven insights for traffic control.
- Enable real-time visualization of traffic patterns.

### Key Features
- **📝 Automatic Number Plate Recognition (ANPR)**
- **🚦 Automatic Traffic Classification and Control (ATCC)**
- **📊 Data interpolation for precise tracking**
- **📈 Visualization tools for actionable insights**

---

## 📂 Folder Structure
```
├── .idea/                       # Project settings and configurations
├── CV_Basics/                   # Computer vision and OCR learning materials
├── Image_processing/            # Preprocessing for better detection
├── Interpolation/               # Scripts for data interpolation
├── Testing/                     # Files for testing and debugging
├── Video_processing/            # Scripts for video visualization
├── YOLO_training/               # YOLO model fine-tuning
├── interpolated_results/        # Refined CSV files after interpolation
├── object_tracker/              # Main vehicle detection and tracking code
├── results/                     # Initial detection results
├── utils/                       # Helper functions for OCR corrections
├── .gitignore                   # Rules to ignore specific files in Git
├── main.py                      # Main script to execute the workflow
└── requirements.txt             # Dependencies for the project
```

---

## 🔄 Workflow
1. **Initial Detection:** Run `main.py` to detect vehicles and generate a CSV file in the `results/` directory.
2. **Data Interpolation:** Execute `add_missing_data.py` to fill in missing data and create an enhanced CSV file in `interpolated_results/`.
3. **Visualization:** Use `visualize.py` to create a video representation of the processed data, saved in the `output_videos/` directory.

---

## 🛠️ Setup and Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Mittalkabir/ANPR_and_ATCC_for_Smart_Traffic_Management
   ```

2. **Set Up Environment:**
   Create and activate a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure Environment Variables:**
   - If applicable, create a `.env` file from `.env.example` and update necessary configurations.

---

## 🚀 Running the Project

1. **Run Main Detection Script:**
   ```bash
   python main.py
   ```

2. **Perform Data Interpolation:**
   ```bash
   python add_missing_data.py
   ```

3. **Generate Visualization Video:**
   ```bash
   python visualize.py
   ```

---

## ✨ Highlights
- **Smart Traffic Automation:** Real-time vehicle detection and classification.
- **Data-Driven Insights:** Accurate tracking through data interpolation.
- **Visual Analytics:** Clear and actionable video visualizations for traffic management.

---

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/Mittalkabir/ANPR_and_ATCC_for_Smart_Traffic_Management) file for details.

---

Explore the repository to discover how ANPR and ATCC are transforming traffic systems for the future!