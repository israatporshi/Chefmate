# 🍳 **ChefMate — Your Smart AI Recipe Assistant**

ChefMate is an **AI-powered recipe recommendation web application** built with **Python Flask**.  
It helps users discover the perfect dish from ingredients they already have at home.  
Using **Natural Language Processing (spaCy)**, **Fuzzy Matching**, and **Machine Learning**,  
ChefMate can normalize ingredients, handle typos, and predict the most suitable recipes and cuisines —  
all through a clean, user-friendly interface.

---

## 🚀 **Features**

### 🧠 **AI & NLP Intelligence**
- 🥫 **Ingredient Normalization:** Understands ingredient variations (e.g., _tomatoes → tomato_) using spaCy.
- ✏️ **Fuzzy Matching:** Suggests recipes even with spelling mistakes or slight variations.
- 🧂 **Ingredient Categorization (Planned):** Group ingredients by type (spices, dairy, etc.) for smarter results.

### 🤖 **Machine Learning Predictions**
- 🔍 Predicts **recipe names** and **cuisines** based on ingredient combinations.
- 📊 Trained with a **Kaggle dataset (~643 MB)** for flavor and cuisine pattern analysis.

### 💡 **Smart User Experience**
- 🧭 Clean, responsive **Flask frontend**.
- 🎛️ Dropdown filters for:
  - 🥗 Cuisine  
  - 🥦 Diet Type  
  - 🍛 Meal Type  
- ⚡ Displays **matching score** with each recipe for transparency.

### 🔮 **Future Upgrades**
- 🔍 Live search bar  
- 🌎 Filter by difficulty level  
- ❤️ Save favorite recipes  
- ⭐ Add ratings & comments  
- 🛒 Smart shopping list export  

---

## 🏗️ **Tech Stack**

| Category | Technology |
|-----------|-------------|
| 🖥️ Backend | Flask (Python) |
| 🎨 Frontend | HTML5, CSS3, JavaScript |
| 🧠 AI/NLP | spaCy, FuzzyWuzzy |
| 🤖 Machine Learning | Scikit-learn, Pandas, NumPy (planned) |
| 📂 Dataset | Kaggle Recipe Dataset |
| ⚙️ Environment | Virtualenv / Conda |

---

## ⚙️ **Installation & Setup**

Follow these steps to run **ChefMate** locally 👇  
### 1️⃣ **Clone the Repository**
### 2️⃣ **Create and Activate Virtual Environment**

#### 🪟 **For Windows:**
python -m venv venv
venv\Scripts\activate
🍎 For macOS/Linux:
bash
Copy code
python3 -m venv venv
source venv/bin/activate

3️⃣ Install Dependencies
bash
Copy code
pip install -r requirements.txt

4️⃣ Run the Flask App
bash
Copy code
python app.py

5️⃣ Open in Browser
Visit 👉 http://127.0.0.1:5000/

🧠 How It Works

🥕 User enters ingredients.

🧩 spaCy performs lemmatization & synonym handling.

🔎 Fuzzy Matching compares ingredients against the dataset.

🍲 Displays best-matched recipes with confidence scores.

🤖 (Future) Machine Learning model predicts cuisine & recipe name.

🧩 Project Structure
csharp
Copy code
ChefMate/
│
├── app.py              # Main Flask app
├── utils.py            # NLP + Matching utilities
├── static/             # CSS, JS, Images
├── templates/          # HTML templates
├── models/             # ML model files (planned)
├── data/               # Dataset files
├── requirements.txt    # Dependencies
└── README.md

👩‍💻 Author
Israt Jerin Porshi
📧 ij.porshi@gmail.com
🌐 GitHub Profile : https://github.com/israatporshi
