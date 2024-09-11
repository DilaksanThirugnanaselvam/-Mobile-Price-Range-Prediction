# 📱 Mobile Price Range Prediction

This project builds and trains a simple **Artificial Neural Network (ANN)** model to predict the price range of mobile phones based on their specifications. The prediction is binary, classifying phones into either the **low** or **high** price range. The project uses **TensorFlow** for building the ANN and **Streamlit** for the user interface.

## 📷 Screenshots
![Screenshot 2024-09-11 234623](https://github.com/user-attachments/assets/fa2bc30b-93a9-49a3-ac34-a228c6b0deaa)


## 📋 Table of Contents
- [🔍 Overview](#overview)
- [📊 Dataset](#dataset)
- [🧠 Model Architecture](#model-architecture)
- [⚙️ How to Run](#how-to-run)
- [📂 Project Structure](#project-structure)
- [🎯 Results](#results)
- [🛠️ Technologies Used](#technologies-used)
- [🤝 Contributing](#contributing)
- [📜 License](#license)
- [📑 Contract Details](#contract-details)

## 🔍 Overview
Nimal, a new mobile company owner in Sri Lanka, wants to predict the price range of his company's mobile phones. This project helps Nimal by developing an ANN model to predict the price range using various phone specifications (RAM, internal memory, battery power, etc.).

A simple web application has been built using **Streamlit**, allowing users to input mobile specifications and get instant predictions of whether the mobile falls into a low or high price range.

## 📊 Dataset
The dataset used for this project contains mobile phone specifications along with their respective price ranges (high or low). It is a CSV file with features such as:
- **💾 RAM**: The mobile's RAM size in GB
- **📦 Internal Memory**: The internal memory in GB
- **🔋 Battery Power**: The battery capacity in mAh
- **📏 Pixel Height** and **📏 Width**: The screen resolution
- **⚖️ Mobile Weight**: The weight of the mobile in grams
- Other relevant features for mobile price classification.

## 🧠 Model Architecture
The **Artificial Neural Network (ANN)** consists of:
- **Input Layer**: Takes in all the mobile phone features.
- **1️⃣ First Hidden Layer**: 8 neurons with ReLU activation.
- **2️⃣ Second Hidden Layer**: 4 neurons with ReLU activation.
- **⚙️ Output Layer**: 1 neuron with sigmoid activation for binary classification (high/low price range).

The model is trained for **100 epochs** with a **batch size of 32** using TensorFlow.

## ⚙️ How to Run
### 1. 🚀 Clone the Repository
```bash
git clone https://github.com/your-username/mobile-price-prediction.git
cd mobile-price-prediction
```

### 2. 📦 Install the Required Dependencies
```bash
pip install -r requirements.txt
```

### 3. 💻 Run the Streamlit App
```bash
streamlit run app.py
```

This will start the Streamlit app, where you can input mobile specifications and get price predictions.

## 📂 Project Structure
```
mobile-price-prediction/
│
├── 📁 Mobile Price Classification.csv   # Dataset
├── 📄 app.py                            # Streamlit app code
├── 📄 model.py                          # ANN model architecture and training code
├── 📄 README.md                         # Project documentation
├── 📄 requirements.txt                  # Python dependencies
└── 📦 mobile_price_model_weights.h5     # Pre-trained model weights
```

## 🎯 Results
After training, the ANN model achieved **X% accuracy** on the test set. The model can accurately classify mobile phones into high or low price ranges based on user input in the Streamlit app.

## 🛠️ Technologies Used
- **Python** 🐍: Programming language
- **TensorFlow** 🧠: For building and training the ANN model
- **Streamlit** 🌐: For creating the user interface
- **Pandas** 🐼: For data manipulation
- **Scikit-learn** 📊: For data splitting and preprocessing

## 🤝 Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Contributions are welcome!

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author
Dilaksan Thirugnanaselvam - AI Engineer

## 📫 Contact
Email: thirudilak131@gmail.com

LinkedIn: [Dilaksan Thirugnanaselvam](https://www.linkedin.com/in/dilaksan-thirugnanaselvam-65641b262/)

Phone: +94-0788702104


