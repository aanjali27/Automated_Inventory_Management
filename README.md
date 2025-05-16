Smart Inventory Management System with Google Sheets, Forms & AI
A real-world automation solution designed to help small enterprises manage inventory effortlessly using Google Forms, Sheets, Apps Script, and a touch of AI.

🚀 What This Project Does
This system allows small businesses to:

✅ Automatically update inventory when employees fill out a form

📬 Get email alerts when stock is low

📊 View a real-time dashboard of stock levels

📅 Receive daily stock usage reports

🤖 Predict how long current stock will last (basic AI logic using usage history)

🔧 How It Works
1. Google Form Input
Employees submit product usage via a simple form:

Product (Dropdown auto-synced)

Quantity

Action: Add or Remove

2. Google Sheet Inventory
Sheet tracks stock, reorder level, product details

Automatically updates when form is submitted

3. Apps Script Automation
onFormSubmit(): Updates inventory

checkInventoryLevels(): Sends low stock alert emails

dailyStockReport(): Summarizes stock removed each day

updateFormDropdownFromSheet(): Keeps form synced with product list

predictStockDuration(): Forecasts how many days stock will last

4. Real-Time Dashboard
Conditional formatting for low stock

Charts for inventory and trends

📈 Technologies Used
Google Sheets

Google Forms

Google Apps Script (JavaScript-based)

Basic AI logic using average daily usage

💡 Why This Project?
As part of my MBA in AI & Data Science, I created this solution to show how automation and AI can solve real-world problems for small businesses — without needing expensive ERP systems.

✅ Business Benefits
No manual updates or stock errors

Timely reorder decisions

Better planning using AI-based predictions

Fully cloud-based and free to use

📂 Files Included
Google Apps Script (Code.gs)

Sample Google Sheet template

Setup Instructions (see below)

🛠️ Setup Instructions
Copy the Google Sheet template.

Create a Google Form linked to the sheet

Paste the Apps Script code into Extensions > Apps Script

Set up triggers for onFormSubmit, checkInventoryLevels, etc.

Customize email and form fields as needed

📬 Contact / Questions
Feel free to reach out if you want to use or extend this:

📧 Email: aaaanjali62email@example.com

💼 LinkedIn: www.linkedin.com/in/anjalisingh-

🌟 Showcase
This project is part of my portfolio demonstrating how AI & automation can drive business transformation.

If you find this useful, please ⭐️ the repo and share!
