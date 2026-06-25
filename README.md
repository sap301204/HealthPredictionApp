# MIRA AI - Health Prediction Application (v2.5)

An intelligent healthcare intelligence panel (MIRA v2.5 Cluster Core) built to manage patient records, perform synchronous format validation, compute real-time biomarker visualizations, and execute AI/ML-driven diagnostic health risk inferences.

## 🚀 Features

- **Full CRUD Management:** Create, Read, Update, and Purge patient records smoothly via a single-page secure interface.
- **Synchronous Data Validation Layer:** Custom input format verification preventing chronological future dates for Date of Birth, verifying email structures, and enforcing strict numeric validation for biomarker values.
- **AI/ML Diagnostics Engine:** Integrates predictive analytics to evaluate risk intervals (e.g., Hypoglycemia, Hypercholesterolemia) and output clinical insights into the user remarks ledger.
- **Dynamic Telemetry Charts:** Renders interactive real-time data comparisons using Chart.js to map user patient metrics against standard clinical medical baselines.

## 🛠️ Technology Stack

- **Backend Logic:** Python / Flask Framework
- **Persistent Storage:** SQLite3 (Relational Database)
- **Frontend Layer:** Responsive HTML5 / CSS3 / Bootstrap 5 / Chart.js / Bootstrap Icons

## 📂 Project Directory Structure

```text
HealthPredictionApp/
│
├── templates/
│   └── index.html          # Responsive dark-mode dashboard interface
│
├── app.py                  # Main Flask backend application & CRUD routing logic
├── models.py               # SQLite database table schema initialization
├── requirements.txt        # Staged Python package dependencies list
├── .gitignore              # Instructions telling Git files/folders to bypass tracking
└── README.md               # Production-ready documentation manual
