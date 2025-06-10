# ✈️ Flight Tracker App (Streamlit)

A simple and interactive flight tracker built with **Python** and **Streamlit**, using the [AviationStack API](https://aviationstack.com/). This app allows users to search for live flight information using just a flight IATA number (like AI302).

---

## 🌟 Features

- 🔍 Real-time flight status lookup
- 🖥️ Streamlit-based web interface (no frontend code needed)
- 🔐 API key stored securely using `.env` file
- 🧼 Clean UI with automatic error handling

---

## 🛠️ Tech Stack

- Python
- Streamlit
- AviationStack API
- Requests
- python-dotenv

---

## 🚀 How to Run the App Locally

```bash
# 1. Clone this repository
git clone https://github.com/your-username/flight-tracker.git
cd flight-tracker

# 2. Create a .env file and add your API key
echo "AVIATIONSTACK_API_KEY=your_actual_api_key_here" > .env

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Streamlit app
streamlit run flight_tracker_web.py
```
## 📦 Deployment (Streamlit Cloud)
1. Visit https://streamlit.io/cloud  
2. Sign in with GitHub  
3. Connect this repo and click Deploy  
4. Add AVIATIONSTACK_API_KEY in the “Secrets” tab under Settings 
