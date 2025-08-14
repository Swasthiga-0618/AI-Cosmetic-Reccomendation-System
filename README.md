# 💄 AI Cosmetic Recommendation System

A facial-recognition-powered cosmetic recommendation tool that uses **OpenCV** to detect facial features (e.g., skin tone, face region) and aims to integrate **machine learning** for smarter, more personalized product recommendations.

This project is ideal for those interested in **computer vision**, **ML integration**, and **beauty tech**.

---

## 🚀 Features

- 📸 Facial analysis using OpenCV
- 🤖 (In Progress) ML-based recommendation system based on user data
- 💄 Cosmetic product suggestions tailored to skin tone/type
- 🌐 UI with **HTML/CSS/JS** and optional **Streamlit**
- 🧠 Dataset expansion with real-world beauty products

---

## 🛠️ Tech Stack

- **Python**
- **OpenCV**
- **Jupyter Notebook**
- **Scikit-learn / TensorFlow / ML models** *(planned)*
- **HTML, CSS, JavaScript** (UI)
- **Streamlit** (optional Python-based UI)

---

## 💡 How It Works

1. Users upload a facial image or use webcam input.
2. OpenCV analyzes the face to determine:

   * Skin tone
   * Region of interest (e.g., lips, cheeks)
3. *(Planned)* Machine learning model will:

   * Analyze user data (e.g., age, skin concerns)
   * Recommend products based on historical patterns and similarity
4. The system displays personalized cosmetic suggestions.

---

## 🧠 Recommendation Algorithm

### How Recommendations Are Made
Our system uses a **content-based recommendation approach** to suggest cosmetic products.  
1. **User Input Collection** – Takes preferences or an image for facial analysis.  
2. **Feature Extraction** – Converts skin type, tone, and concerns into a feature vector.  
3. **Similarity Calculation** – Uses cosine similarity to compare user profile with products.  
4. **Filtering Rules** – Removes incompatible items based on skin type, age, etc.  
5. **Ranking & Output** – Recommends top N products based on relevance score.

### Dataset Features Used
| Feature Name           | Description |
|------------------------|-------------|
| Product Name           | Cosmetic/skincare product name |
| Brand                  | Manufacturer |
| Skin Type              | Target type (oily, dry, etc.) |
| Skin Concern           | Problem addressed |
| Ingredients            | Active components |
| Finish/Effect          | Matte, glossy, hydrating |
| SPF                    | Sun protection factor |
| Tone/Shade             | Suitable skin tone |
| Price                  | Price range |
| Rating                 | Average user rating |
| Category               | Product category |

---

## 🤝 How to Contribute

We’re actively looking for contributors who can help with:

* 🖼️ Frontend UI (HTML/CSS/JS or Streamlit)
* 🧠 ML model development (e.g., product clustering, user profiling)
* 📦 Expanding the dataset with real cosmetic products
* 📘 Writing documentation, improving UX, or testing

### Contribution Steps

1. Fork this repo
2. Create a new branch

   ```bash
   git checkout -b feature-branch
   ```
3. Make your changes and commit

   ```bash
   git commit -m "Add your feature"
   ```
4. Push to your branch

   ```bash
   git push origin feature-branch
   ```
5. Open a Pull Request 🎉

---

## 📂 Project Structure

```
├── data/                   # Product datasets
├── notebooks/              # OpenCV and ML notebooks
├── ui/                     # HTML/CSS/JS frontend
├── streamlit_app/          # Streamlit frontend
├── app.py                  # Main Streamlit entry point
├── README.md
└── requirements.txt
```

---

## 📌 Project Roadmap

✅ Facial detection with OpenCV
🛠 ML-based recommendation model *(in progress)*
🛠 Frontend UI improvements (HTML/CSS or Streamlit)
🛠 Expand product database with real brands/shades/types

---

## 👩‍💻 Author

Made with ❤️ by [Kasmya Bhatia](https://www.linkedin.com/in/kasmya-bhatia-8b472a276?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)

Feel free to connect for feedback, contributions, or collaboration.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

