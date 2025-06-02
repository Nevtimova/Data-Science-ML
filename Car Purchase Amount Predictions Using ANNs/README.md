# 📊 Car Purchase Amount Prediction Using Artificial Neural Networks 🚘💰

This project builds a **regression model using an Artificial Neural Network (ANN)** to predict the car purchase amount a customer is likely to spend, based on personal and financial data.

---

## 🚀 Features  

- Loads and processes customer financial data.
- Scales features using **Min-Max scaling**.
- Builds and trains an ANN regression model using **Keras**.
- Visualizes training and validation loss progression.
- Makes predictions on new customer profiles.

---

## 🛠️ Tech Stack  

| Tool/Library   | Purpose                          |
|:---------------|:--------------------------------|
| `Pandas`        | Data manipulation and analysis  |
| `NumPy`         | Numerical computations          |
| `Seaborn`       | Data visualization              |
| `Matplotlib`    | Plotting training results       |
| `Scikit-learn`  | Data scaling and train-test splitting |
| `TensorFlow/Keras` | Neural network modeling      |

---

## 📖 How It Works  

1. **Load and explore the dataset** with customer demographics, financial metrics, and car purchase amounts.
2. **Preprocess the data**:
   - Drop unnecessary columns (e.g., customer names, emails, countries).
   - Split data into features `X` and target `y`.
   - Apply **MinMax scaling** to normalize data.
3. **Split the dataset** into training and test sets.
4. **Build an ANN regression model**:
   - 2 hidden layers with 25 neurons each and **ReLU** activation.
   - 1 output layer with **linear activation**.
5. **Train the model** using **Adam optimizer** and **Mean Squared Error (MSE)** loss.
6. **Visualize model performance** using loss curves.
7. **Make predictions** on new customer data samples.

---

## 📦 Installation  

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow


