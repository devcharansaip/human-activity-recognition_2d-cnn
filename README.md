# Human Activity Recognition using Accelerometer Data

## 📌 Project Overview

This project focuses on **Human Activity Recognition (HAR)** using accelerometer data. The goal is to classify different human activities (e.g., walking, sitting, jogging) based on sensor data using machine learning and deep learning techniques.

The implementation uses a **2D Convolutional Neural Network (CNN)** to learn patterns from time-series accelerometer data.

---

## 📂 Dataset

* Source: [WISDM Dataset](http://www.cis.fordham.edu/wisdm/dataset.php)
* Activities included:

  * Walking
  * Jogging
  * Sitting
  * Standing
  * Upstairs
  * Downstairs

---

## ⚙️ Project Workflow

### 1. Data Loading

* Import raw accelerometer data
* Assign activity labels

### 2. Data Preprocessing

* Handle missing values
* Normalize / standardize features
* Balance dataset across activity classes

### 3. Feature Engineering

* Segment time-series data into frames/windows
* Convert into structured format suitable for CNN

### 4. Model Building

* Implement a **2D CNN model**
* Train on processed dataset
* Evaluate performance using appropriate metrics

---

## 🧠 Model Architecture

* Input: Segmented accelerometer frames
* Layers:

  * Convolutional Layers
  * Pooling Layers
  * Fully Connected Layers
* Output: Activity classification (6 classes)

---

## 📊 Results

* Model performance is evaluated using:

  * Accuracy
  * Loss curves
* (You can update this section with actual results from your runs)

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:

   ```bash
   jupyter notebook
   ```

4. Open:

   ```
   Human_Activity_Recognition.ipynb
   ```

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* TensorFlow / Keras
* Matplotlib

---

## 📁 Project Structure

```
├── Human_Activity_Recognition.ipynb
├── README.md
├── results/
├── requirements.txt
└── data/
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgements

* WISDM Dataset contributors
* Open-source ML community
