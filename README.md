# 📊 CSV to Sales Visualizer

**CSV to Sales Visualizer** is a simple, interactive Python web app that allows users to upload a CSV file containing advertising data (**TV**, **Radio**, **Newspaper**, and **Sales**) and instantly visualize trends, insights, and predictions — all through a clean Gradio interface.

---

## ✨ Features

- 📂 Upload a CSV file with **TV**, **Radio**, **Newspaper**, and **Sales** columns
- 📊 User-friendly **bar**, **line**, and **pie** charts for clear insights
- 🤖 Predict sales using **Linear Regression**
- 🔍 Compare actual vs predicted sales in a **line chart**
- 🛠 Powered by **Gradio**, **Pandas**, **Matplotlib**, **Seaborn**, and **Scikit-learn**

---

## 🧾 Sample CSV Format

Make sure your CSV follows this structure:

```csv
TV,Radio,Newspaper,Sales
230.1,37.8,69.2,22.1
44.5,39.3,45.1,10.4
17.2,45.9,69.3,9.3
...
```

---

## 💻 How to Run the App

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/csv-to-sales-visualizer.git
cd csv-to-sales-visualizer
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
Or manually:
```bash
pip install pandas matplotlib seaborn scikit-learn gradio
```

### 3️⃣ Run the App
```bash
python app.py
```

✅ The Gradio interface will launch in your browser automatically.

---

## 📈 Visual Output Includes

- 📊 Average Advertising Spend (Bar Chart)
- 📉 Sales vs Total Spend (Line Chart)
- 🧩 Ad Spend Distribution (Pie Chart)
- 🔄 Actual vs Predicted Sales (Line Chart)
- 🧠 Model summary with coefficients and R² score

---

## ⚙️ Tech Stack

- 🐍 **Python** – Core programming
- 🧩 **Gradio** – Frontend UI
- 🐼 **Pandas** – Data processing
- 📊 **Matplotlib & Seaborn** – Graphs and charts
- 🤖 **Scikit-learn** – Regression model

---

## 📌 Ideal For

- 📈 Marketing data visualization
- 🎓 Educational demos on regression
- 📊 Business analysis of ad spend
- 👩‍💻 Students learning Python + Data Science

---

## 📝 License

This project is open-source under the **MIT License**.

---

## 🤝 Contributing

Pull requests and suggestions are welcome!  
Feel free to fork the project and customize it to your needs.

---

## 📢 Contact

Have questions or want to share feedback?  
Open an issue or reach out via **GitHub Discussions**.

