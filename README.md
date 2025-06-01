🌾 Crop Type Prediction Using Machine Learning
This project aims to predict the most suitable crop type for a region based on multiple factors such as soil conditions, fertilizer usage, weather, and historical crop yield data. It uses various machine learning models to train on the dataset and evaluate their performance.

📂 Datasets Used
The project combines data from four CSV files:

yield_data.csv: Contains historical crop yield information.

fertilizer.csv: Includes details on fertilizer types and amounts used.

soil_data.csv: Has soil type and nutrient values (like nitrogen, phosphorus, potassium).

weather.csv: Covers climate data such as rainfall and temperature.

🧠 Machine Learning Models Used
Random Forest: Combines several decision trees to make accurate predictions. It is reliable for complex datasets.

Decision Tree: Simple model that follows a series of decisions to predict the crop type.

Support Vector Machine (SVM): Finds the best boundary to separate crop types.

Logistic Regression: Predicts crop types based on probability and is great for simpler relationships in the data.

📊 Visualizations Included
To understand the data better, several visualizations are provided:

Distribution of crop types

Correlation heatmap of features

Yield distribution and boxplots

Fertilizer and soil type distributions

Rainfall patterns by region

Confusion matrix of Random Forest model

Model accuracy comparison

⚙️ How It Works
All datasets are loaded and merged.

Categorical features like crop type and soil type are encoded using LabelEncoder.

Features are standardized using StandardScaler.

The dataset is split into training and testing sets.

Each model is trained and evaluated.

The best-performing model (e.g., Random Forest) is saved using pickle.

A sample input is provided to predict the best crop type.

Results and evaluation metrics are printed along with helpful plots.

🖥️ Technologies Used
Python

Pandas

Scikit-learn

Matplotlib

Seaborn

Pickle

🚀 How to Run in Google Colab
Open Google Colab in your browser.

Upload the four datasets (yield_data.csv, fertilizer.csv, soil_data.csv, weather.csv) by:

Clicking on the folder 📁 icon on the left.

Clicking the upload icon ⬆️ to upload each CSV file.

Copy and paste the Python code from this project into a new notebook cell.

Run the notebook cell by cell.

The model will train and display:

Accuracy results

Classification reports

Graphs for data analysis

Predicted crop for a sample input

✅ Make sure your datasets are named correctly and match those used in the code.
