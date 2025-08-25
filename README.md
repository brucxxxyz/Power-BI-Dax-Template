# Power BI Time Intelligence Measures

This repository contains reusable DAX measures for dynamic weekly and fortnightly reporting in Power BI.
All measures are designed for rolling week logic (Sunday-ending) and use TODAY() to stay current.

## 📦 Included Measures

- Last Week Sales
- Previous Week Sales
- Last Fortnight Sales
- Previous Fortnight Sales

## 🛠 Usage

1. Ensure your Date table is marked as a Date Table in Power BI.
2. Copy the DAX expressions from `/dax/` into your model.
3. Adjust [Sales] to match your actual base measure name.

## 🧠 Author

Bruce - Data Scientist (Auckland, NZ)
