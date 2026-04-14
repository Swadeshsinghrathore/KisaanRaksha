# Last Update


https://github.com/user-attachments/assets/3fb9daa1-7362-435e-b4b9-f2660a531338


![Uploading image.png…]()
![Uploading image.png…]()



# KisaanRaksha 🌾

**KisaanRaksha** is an AI-powered platform to help Indian farmers with:
- 📊 Crop risk assessment
- 💰 Market (mandi) price forecasting
- 🌱 Crop recommendations
- 🏛️ Government scheme discovery
- 🌦️ Weather alerts

## Project Structure
```
kisaanraksha/
├── frontend/       # HTML, CSS, JS UI
├── backend/         # Python backend (Flask/FastAPI)
│   ├── models/      # ML model definitions
│   ├── services/    # External API integrations
│   ├── data/        # Static datasets
│   └── trained_models/  # Serialised .pkl / .h5 files
├── notebooks/       # Jupyter training notebooks
├── requirements.txt
└── .env             # Environment variables (never commit!)
```

## Setup
```bash
pip install -r requirements.txt
cp .env.example .env   # fill in your API keys
python backend/app.py
```
