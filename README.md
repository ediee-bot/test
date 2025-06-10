# test
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

1. **Clone this repository**  
   ```bash
   git clone https://github.com/your-username/flight-tracker.git
   cd flight-tracker
Create a .env file and add your AviationStack API key:

ini
Copy
Edit
AVIATIONSTACK_API_KEY=your_actual_api_key_here
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the Streamlit app

bash
Copy
Edit
streamlit run flight_tracker_web.py
📦 Deployment
You can deploy this on Streamlit Cloud for free:

Visit https://streamlit.io/cloud

Sign in with GitHub

Connect this repo and click Deploy

Add the AVIATIONSTACK_API_KEY in the “Secrets” tab under Settings
<details>
<summary>📋 One-Click Setup Instructions</summary>

```bash
# Step 1: Clone the repository
git clone https://github.com/your-username/flight-tracker.git
cd flight-tracker

# Step 2: Create a .env file and add your API key
echo "AVIATIONSTACK_API_KEY=your_actual_api_key_here" > .env

# Step 3: Install dependencies
pip install -r requirements.txt

# Step 4: Run the app
streamlit run flight_tracker_web.py
</details> ```
