# 🛠️ Turbofan Engine Remaining Useful Life (RUL) Predictor

Welcome to the **Turbofan RUL Prediction App** — a machine learning-powered tool that estimates how many operational cycles are left before a turbofan engine fails.

🔗 **Try it now**: [Live on Hugging Face Spaces 🚀](https://huggingface.co/spaces/Devalekka/Turbofan_remaining_lifecycle_predictor)

---

## 🔍 What is this?

This app predicts the **Remaining Useful Life (RUL)** of a turbofan engine based on the latest sensor readings. It's designed for **predictive maintenance**, helping engineers avoid unexpected failures and plan ahead efficiently.

---

## 👥 Who is this for?

- Aerospace Engineers  
- Predictive Maintenance Teams  
- Mechanical & Industrial Engineers  
- Students & Researchers in AI for IoT / Industry 4.0

---

## 🧠 How it works

- Uses time-series data from 21 engine sensors  
- Features are engineered using **mean**, **slope**, and **last value** of each sensor  
- Trained using a **stacked ensemble** of Random Forest, CatBoost, and LightGBM  
- UI built with **Gradio** and hosted on Hugging Face

---

## 🎮 How to Use

- 📄 **Upload** a `.csv` file with shape **(30 rows × 21 columns)** (sensor values)
- 🧪 Or **manually enter** 30 recent readings for each of the 21 sensors
- 🎲 You can also **autofill dummy data** to test the app
- 💡 Get an instant prediction of the engine’s remaining life (in cycles)

---

## 🛠️ Tech Stack

- Python, Pandas, NumPy  
- Scikit-learn, LightGBM, CatBoost  
- Gradio UI  
- Hugging Face Spaces for deployment

---

## 🙋‍♀️ Created by

**Devalekka**  
👩‍💻 AI & Data Science student | Passionate about real-world ML solutions  
📅 June 2025

---

> Have ideas, suggestions, or want to collaborate?  
Feel free to connect or drop feedback!

