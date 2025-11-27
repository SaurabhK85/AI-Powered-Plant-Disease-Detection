# 🌾 AI-Based Plant Disease Detection

An intelligent web-based solution that assists farmers and agricultural professionals in identifying plant diseases by analyzing leaf images. Users can upload a photo of a plant leaf, and the system predicts the disease along with practical treatment suggestions in both English and Hindi.

---

## 📷 Preview

![Application Preview](static/demo/demo_screenshot.png)
*(Update this path with your actual screenshot if needed)*

---

## ✨ Key Highlights

* 🍃 Upload leaf images to check for possible diseases.
* 🧪 Real-time disease prediction using a trained DenseNet121 deep learning model.
* 📝 Treatment tips and prevention measures displayed in **English & Hindi**.
* 📱 Modern, responsive UI designed with **Bootstrap 5** for smooth user experience.
* 🔒 Safe and controlled image upload mechanism.
* 💻 Works efficiently across different browsers and devices.

---

## 🛠️ Technology Stack

* **Frontend:** HTML, CSS, Bootstrap 5
* **Backend:** Flask (Python 3.12.2)
* **Machine Learning Model:** DenseNet121 (TensorFlow / Keras)
* **Deployment:** Localhost (extendable to Heroku, AWS, or PythonAnywhere)

---

## 📁 Folder Structure

```
├── app.py                  # Core Flask application
├── model/
│   └── plant_disease_model.h5   # Trained DenseNet121 model
├── static/
│   ├── uploads/            # Stores uploaded leaf images
│   └── demo/               # Screenshots and demo assets
├── templates/
│   ├── index.html          # Landing page
│   ├── detect.html         # Image upload interface
│   ├── predict.html        # Result display page
│   └── contact.html        # Contact details page
├── requirements.txt        # Dependency list
└── README.md               # Project documentation
```

---

## ⚙️ Setup & Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/plant-disease-detection-app.git
cd plant-disease-detection-app
```

### 2. Create and activate virtual environment

```bash
python -m venv venv
source venv/bin/activate
# For Windows: venv\Scripts\activate
```

### 3. Install required packages

```bash
pip install -r requirements.txt
```

### 4. Start the application

```bash
python app.py
```

### 5. Access in browser

Open your browser and go to:
👉 [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

---

## 🧠 Model Information

* **Architecture:** DenseNet121
* **Framework:** TensorFlow / Keras
* **Input Size:** 224 x 224 x 3
* **Supported Classes:** 38 plant disease categories (PlantVillage dataset)
* **Validation Accuracy:** Approximately 96%
* **Remedy System:** Suggestions based on agricultural expert guidelines, shown bilingually

---

## 🔗 Important Routes

* `/` – Main Home Page
* `/detect` – Image Upload & Detection Page
* `/predict` – Shows Prediction & Recommended Remedies
* `/contact` – Contact Information Page

---

## 📞 Contact Details

**Saurabh Kumar**
📧 Email: [skbarh85@gmail.com](mailto:skbarh85@gmail.com)
📱 Phone: +91-9430263683

---

## 📄 License

This project is released under the MIT License. You are free to use, modify, and distribute it for personal or educational purposes.

---

## 🙌 Credits

* PlantVillage Dataset – Penn State University
* TensorFlow & Keras Development Team
* Bootstrap 5 UI Framework

---

## 🚀 Planned Enhancements

* Cloud deployment on AWS / Heroku
* Disease severity level estimation
* Smart agricultural chatbot with multilingual support
* IoT integration for real-time farm monitoring

---

