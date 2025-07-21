

👤 Author
GODAVARI ADITYA VENKAT
🎓 Aditya University
📧 adityagodavari49@gmail.com

You said:
change mail to adityagodavari49@gmail.com


ChatGPT said:
Here’s your updated README.md file with the email changed to adityagodavari49@gmail.com:



A user-friendly web application built with **Python** and **Streamlit** that allows cafeteria staff to manage and display weekly food menus interactively and securely.

---

## 📌 Features

- 🔐 **Admin Login**: Secure access to modify menu items.
- 🎨 **Theme Selector**: Customize the appearance with multiple color themes.
- 📅 **Day Selector**: Display menu items based on the selected day.
- 🍽️ **Meal Type Selector**: Choose between Breakfast, Lunch, Snacks, or Dinner.
- 🗂️ **Category-wise Listing**: Menus are grouped by categories like North Indian, Quick Bites, etc.
- ➕ **Add/Delete Menu Items**: Real-time updates to the JSON-based menu system.
- 💾 **JSON Storage**: All menu data is stored and retrieved from a local JSON file.
- ⚡ **Fast Deployment**: Easily runs locally or can be hosted using Streamlit Cloud.

---

## 🧰 Tech Stack

| Component      | Technology       |
|----------------|------------------|
| Programming    | Python 3.10+      |
| Framework      | Streamlit         |
| Data Storage   | JSON              |
| Editor         | VS Code           |
| Deployment     | Localhost / Streamlit Cloud |

---

## 📸 Screenshots

### Blue Theme - Thursday Lunch
![Blue Theme](screenshots/blue-theme-lunch.png)

### Violet Theme - Monday Breakfast
![Violet Theme](screenshots/violet-theme-breakfast.png)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/cafeteria-menu-display.git
cd cafeteria-menu-display
2. Install Requirements
bash
Copy
Edit
pip install streamlit
3. Run the App
bash
Copy
Edit
streamlit run app.py
🗂️ Project Structure
css
Copy
Edit
cafeteria-menu-display/
├── app.py
├── menu.json
├── README.md
├── requirements.txt
└── screenshots/
    ├── blue-theme-lunch.png
    └── violet-theme-breakfast.png
🛡️ Admin Access
To add or remove menu items, enter the admin password in the sidebar. (You can configure the password inside the app.py file.)

🧱 JSON Menu Format
json
Copy
Edit
[
  {
    "day": "Monday",
    "meals": {
      "Breakfast": [
        {
          "category": "Quick Bites",
          "items": [
            { "name": "Poha", "price": 20 },
            { "name": "Upma", "price": 20 }
          ]
        }
      ]
    }
  }
]
