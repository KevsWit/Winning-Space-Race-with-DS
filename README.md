# 🚀 SpaceX Launch Analysis & Prediction Project

This project explores SpaceX Falcon 9 launch records to uncover insights and build predictive models that determine the likelihood of a successful rocket landing. It combines **data collection**, **visual analytics**, and **machine learning** to support SpaceX's mission of reusable spaceflight.

---

## 📂 Project Structure

- `data/` – CSV files and datasets from web scraping and API
- `notebooks/` – Jupyter Notebooks with data wrangling, EDA, modeling, and visualization
- `README.md` – Project overview and documentation

---

## 📊 Key Steps

### 1. Data Collection  
- Fetched structured launch data from the **SpaceX REST API**.  
- Used **web scraping** to extract additional launch metadata (HTML parsing with BeautifulSoup).  
- All data was loaded and processed using **Pandas**.

### 2. Data Wrangling & Exploration  
- Cleaned and transformed data (e.g., payload, launch site, booster versions).  
- Used **SQL queries**, **Matplotlib**, **Seaborn**, and **Folium** for exploratory data analysis.  
- Mapped launch sites and visualized proximity to coastlines, railways, and cities.

### 3. Dashboard Development  
- Built an interactive dashboard using **Plotly Dash**.  
- Visualized success rates, payload trends, and booster performance by site.  
- Enabled user interaction with dropdowns and sliders.

### 4. Predictive Modeling  
- Applied **Logistic Regression**, **SVM**, **Decision Tree**, and **KNN** classifiers.  
- Tuned models using **GridSearchCV** and evaluated performance via accuracy and confusion matrix.  
- **SVM achieved the highest accuracy (100%)**, followed by Logistic Regression.

---

## ✅ Key Findings

- **KSC LC-39A** had the highest launch success rate among all SpaceX sites.
- **Payloads between 4000–6000 kg** showed better landing success.
- Certain booster versions consistently performed better under specific payload ranges.
- **SVM was the most reliable model** for predicting launch success.

---

## 🛠️ Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- SQL (SQLite)
- Plotly Dash
- Folium
- BeautifulSoup (for Web Scraping)
- Jupyter Notebook

---

## 📌 Author

**[Kevin Castillo]**  
Data Science Student @ IBM / Coursera  
GitHub: [CC0 1.0 Universal]  
Email: [kev.gcastillo@outlook.com]

---

## 📄 License

This project is open-source and available under the [CC0 1.0 Universal](LICENSE).
