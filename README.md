# 🚗 Vehicle CO₂ Emissions Prediction using Deep Learning

## 📌 Project Overview
This project focuses on predicting **vehicle CO₂ emissions** using a **Deep Learning regression model** built with a fully connected neural network.  
The goal is to model the complex, non-linear relationships between vehicle characteristics and environmental impact.

The project demonstrates how **neural networks** can be applied to structured tabular data for regression tasks and is designed as a **portfolio-grade project** suitable for both academic and industry evaluation.

This project is suitable for:
- Master’s degree applications
- Machine Learning / Deep Learning coursework
- Data Science & ML engineering roles
- Environmental and sustainability-focused research

---

## 📊 Dataset Description
The dataset contains numerical vehicle attributes along with their corresponding CO₂ emission values.

**Target variable:**
- `out1` → CO₂ emissions (g/km)

**Input features include:**
- Engine-related specifications
- Fuel consumption indicators
- Vehicle mechanical characteristics

All features are numerical, making the dataset suitable for neural network regression models.

---

## 🔍 Exploratory Data Analysis (EDA)
Exploratory Data Analysis was performed to understand:
- Distribution of CO₂ emission values
- Feature correlations and dependencies
- Relationships between vehicle specifications and emissions

Key visualizations include:
- Target variable distribution plot
- Correlation heatmap of numerical features

EDA helped confirm the suitability of the dataset for non-linear modeling.

---

## 🧠 Deep Learning Model Architecture
A **feedforward neural network** was implemented using Keras:

- Input layer corresponding to vehicle features
- Hidden layer with 55 neurons and ReLU activation
- Output layer with a single neuron for regression output

The model was trained using:
- **Loss function:** Mean Squared Error (MSE)
- **Optimizer:** Adam
- **Epochs:** 500

This architecture balances model capacity and computational efficiency.

---
## 🧩 Neural Network Visualization

To improve model interpretability and transparency, the neural network architecture was visualized using the **keras_visualizer** library.

The visualization provides a clear graphical representation of:
- Input layer dimensions
- Hidden layer structure and neuron count
- Output layer configuration
- Overall network depth and connectivity

This step enhances model explainability, which is particularly important in:
- Academic research and coursework
- Model documentation and presentation
- Communicating deep learning designs to non-technical stakeholders

The generated diagram is saved as an image file and can be included in reports or documentation.


---


## ⚙️ Model Training & Evaluation
The dataset was split into training and testing subsets using an 80/20 split.

Model performance was monitored through:
- Training loss (MSE)
- Loss convergence visualization
- Comparison between predicted and actual CO₂ values

A prediction example was also generated to demonstrate real-world inference capability.

---

## 📈 Results & Observations
- The neural network successfully learned non-linear patterns in the data
- Training loss decreased consistently, indicating stable convergence
- The model demonstrated strong predictive capability on unseen test samples

This confirms the effectiveness of deep learning for regression on structured environmental data.

---

## 🛠️ Tools & Technologies
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Keras (TensorFlow backend)
- Scikit-learn
- Jupyter Notebook / Kaggle Notebook

---

## 🎯 Why This Project Matters
This project demonstrates:
- Practical application of deep learning to environmental data
- Ability to design and train neural networks for regression
- Strong data preprocessing and EDA skills
- Understanding of model convergence and loss analysis

It reflects both **academic depth** and **industry-ready machine learning practice**.

---

## 🚀 Future Improvements
- Feature scaling and normalization
- Validation set and early stopping
- Hyperparameter tuning
- Comparison with classical ML models
- Model generalization evaluation (MAE, RMSE, R²)

---

## 👤 Author
**Mohamad Nahvi**  
Aspiring Data Scientist | Machine Learning & Deep Learning 
Enthusiast  









