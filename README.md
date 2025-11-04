# 🧾 Streamlit + Snowflake Pending Orders App

A companion application to the **Smoothie App**, built with **Streamlit** and **Snowflake**, that allows you to **view and manage pending smoothie orders** in real time.  
It connects directly to the same Snowflake database to display unfilled orders and lets you update their status interactively from a simple web interface.

---

## 🍍 Description

The **Pending Orders App** is designed to complement the Smoothie creation app.  
It provides an intuitive way to review, edit, and mark smoothie orders as completed — all within a few clicks.  

**Main features:**
- Displays pending smoothie orders from Snowflake  
- Interactive data editing with Streamlit’s built-in editor  
- One-click update of order status back into Snowflake  
- Real-time data synchronization between both apps  
- Clean and minimal design for operational simplicity  

---

## ⚙️ Installation

To install and run the app, follow these steps:

1. **Clone this repository:**
   ```bash
   git clone https://github.com/user/pending-orders-app.git
   cd pending-orders-app

2. **Create and activate a virtual environment:**
   python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

3. **Install dependencies:**
   pip install -r requirements.txt

   Create a file named .streamlit/secrets.toml in the project folder and include your Snowflake credentials:
4. **Set up your Snowflake connection:**
[connections.snowflake]
user = "YOUR_USER"
password = "YOUR_PASSWORD"
account = "YOUR_ACCOUNT"
database = "YOUR_DATABASE"
schema = "YOUR_SCHEMA"
warehouse = "YOUR_WAREHOUSE"

🚀 Usage

Once the installation is complete:

Run the application:

streamlit run app.py


Open your browser:
Go to http://localhost:8501
 and start managing smoothie orders.

View all pending orders retrieved from Snowflake

Edit order details such as the ORDER_FILLED status

Submit updates directly to the Snowflake database

✨ A seamless follow-up to the Smoothie App — turning data into action with just one click.
