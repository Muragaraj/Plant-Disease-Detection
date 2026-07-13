# 🌿 Plant Disease Detection Using Deep Learning

##  Project Overview

Plant diseases can significantly reduce crop yield and affect food production. Early detection helps farmers take timely action to prevent the spread of diseases.

This project is a **Plant Disease Detection System** developed using **Deep Learning (Convolutional Neural Networks - CNN)**. Users can upload an image of a plant leaf through a **Streamlit web application**, and the trained model predicts the disease affecting the plant.

The application provides a simple, user-friendly interface for quick disease identification without requiring any technical knowledge.

---

#  Features

* Upload plant leaf images
* Automatic image preprocessing
* Disease prediction using a trained CNN model
* Displays predicted disease name
* Shows prediction confidence (if implemented)
* Fast and easy-to-use Streamlit interface
* Responsive web application
* Can be deployed online using Streamlit Community Cloud

---

# Technologies Used

| Technology              | Purpose                   |
| ----------------------- | ------------------------- |
| Python                  | Programming Language      |
| Streamlit               | Web Application Framework |
| TensorFlow / Keras      | Deep Learning Model       |
| NumPy                   | Numerical Computation     |
| Pillow (PIL)            | Image Processing          |
| OpenCV *(Optional)*     | Image Processing          |
| Matplotlib *(Optional)* | Visualization             |

---

#  Project Structure

```text
Plant-Disease-Detection/
│
├── app.py                 # Main Streamlit application
├── model.h5               # Trained CNN model
├── requirements.txt       # Required Python libraries
├── README.md
├── assets/
│   ├── logo.png
│   └── background.jpg
├── utils.py               # Image preprocessing functions
└── sample_images/
```

---

#  Installation

Clone the repository:

```bash
git clone https://github.com/Muragaraj/Plant-Disease-Detection.git
```

Go to the project directory:

```bash
cd Plant-Disease-Detection
```

Create a virtual environment *(Optional but Recommended)*:

```bash
python -m venv venv
```

Activate the virtual environment:

### Windows

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
source venv/bin/activate
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

#  Run the Application

Start the Streamlit application:

```bash
streamlit run app.py
```

Open your browser and visit:

```text
http://localhost:8501
```

---

#  Model Workflow

```text
Leaf Image
      │
      ▼
Image Upload (Streamlit)
      │
      ▼
Image Preprocessing
      │
      ▼
CNN Model Prediction
      │
      ▼
Disease Classification
      │
      ▼
Display Prediction
```

---

# How to Use

1. Launch the Streamlit application.
2. Upload a clear image of a plant leaf.
3. Wait a few seconds while the model processes the image.
4. View the predicted plant disease.
5. Repeat with different images if needed.

---

#  Dataset

This project is trained using the **PlantVillage Dataset**, which contains thousands of labeled images of healthy and diseased plant leaves.

Dataset includes multiple crops and disease classes such as:

* Tomato
* Potato
* Pepper
* Corn
* Apple
* Grape
* Peach
* Strawberry
* Healthy Leaves

---

#  Objectives

* Detect plant diseases from leaf images.
* Improve early disease diagnosis.
* Provide an easy-to-use web application.
* Support smart agriculture using Artificial Intelligence.

---

#  Applications

* Smart Agriculture
* Precision Farming
* Crop Health Monitoring
* Agricultural Research
* Farmer Assistance
* Educational Projects

---

# Future Enhancements

* Mobile application integration
* Real-time disease detection using a camera
* Disease treatment recommendations
* Fertilizer suggestions
* Weather-based disease prediction
* Multi-language support
* Cloud database integration
* Support for additional crop species

---

#  Author

**Murugaraj V.**

B.Tech – Information Technology

---

# License

This project is intended for educational and research purposes. MIT License.

---

# ⭐ Support

If you find this project helpful, please consider giving it a ⭐ on GitHub.
