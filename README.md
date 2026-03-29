# RenewCred EV Telemetry Intelligence

End-to-end AI/ML pipeline on real MQTT telemetry from a 3-wheeler EV fleet in India.
Built as part of RenewCred's Data Engineer technical assignment (March 2026).

## Tasks
- **Task 1**: Data Ingestion Pipeline & EDA
- **Task 2**: Battery SoC Prediction & BMS Anomaly Detection
- **Task 3**: GPS Accuracy Validation & Route Intelligence

## Setup
```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Project Structure
```
├── data/raw/          ← raw telemetry CSV (not pushed to GitHub)
├── notebooks/         ← Jupyter notebooks per task
├── models/            ← saved ML models
├── outputs/           ← reports, CSVs, charts
└── src/               ← reusable Python modules
```

