# 🏆 BTK Datathon 2024 Project

This repository contains the solution for the BTK Datathon 2024 competition, where machine learning models were applied to real-world data to solve a given problem. The project includes data analysis, feature engineering, model training, and evaluation.

## 📈 Results

- **Kaggle Score (RMSE):** 8.333676

## 📁 Project Structure

The repository includes the following main directories and files:

- `datathon-2024/`: Jupyter notebooks containing data analysis and modeling work.
- `python-script/`: Python script files that automate the model training and prediction process.
- `labels/` and `orange-files/`: Additional files related to the dataset and resources.
- `.gitattributes` and `.gitignore`: Git configuration files.
- `LICENSE`: License information for the project.

## 🚀 Setup and Usage

To run the project on your local machine, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/haydarkadioglu/btk-datathon24.git
   cd btk-datathon24
   ```

2. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

   *Note: If the `requirements.txt` file is not available, you may need to install the required libraries manually.*

3. **Explore the Jupyter Notebooks:**

   You can explore the data analysis and modeling steps in the Jupyter Notebooks located in the `datathon-2024/` directory.

4. **Run the Python scripts:**

   You can use the scripts in the `python-script/` directory to automate the training and prediction processes. For example:

   ```bash
   python python-script/train_model.py
   ```

## 🧑‍💻 Model Evaluation

Here is a list of models used in this project and their corresponding RMSE values:

| Model                            | RMSE       |
|----------------------------------|------------|
| CatBoost Regressor               | 8.333676   |
| Light Gradient Boosting Machine  | 8.423249   |
| Hist Gradient Boosting Regressor | 8.424122   |
| Extreme Gradient Boosting (XGBoost) | 8.466591 |
| Random Forest Regressor          | 8.779624   |
| Gradient Boosting Regressor      | 8.933812   |
| Extra Trees Regressor            | 9.111128   |
| AdaBoost Regressor               | 11.895464  |
| Decision Tree Regressor          | 12.420058  |
| Least Angle Regression           | 12.440110  |
| Linear Regression                | 12.440110  |
| Ridge Regression                 | 12.440112  |
| Bayesian Ridge                   | 12.440123  |
| Lasso Regression                 | 13.115540  |
| Lasso Least Angle Regression     | 13.115547  |
| Huber Regressor                  | 13.672625  |
| Elastic Net                      | 14.861649  |
| K Neighbors Regressor            | 16.959582  |
| Orthogonal Matching Pursuit      | 18.182695  |
| Dummy Regressor                  | 18.236071  |

### Top Performing Models:

- **CatBoost Regressor:** RMSE = 8.333676
- **Light Gradient Boosting Machine:** RMSE = 8.423249
- **Hist Gradient Boosting Regressor:** RMSE = 8.424122
- **Extreme Gradient Boosting (XGBoost):** RMSE = 8.466591

These models, based on gradient boosting techniques, demonstrate superior performance compared to others in the list.

### Gradient Boosting Algorithms:

- **CatBoost:** CatBoost is a high-performance algorithm developed by Yandex, designed to efficiently handle categorical features and often outperforms other gradient boosting algorithms.
- **LightGBM:** Developed by Microsoft, LightGBM is known for its speed and efficiency, particularly with large datasets. It uses a leaf-wise tree growth strategy.
- **Hist Gradient Boosting Regressor:** A histogram-based implementation of gradient boosting, optimized for speed and memory efficiency.
- **XGBoost:** Known for its speed and high performance, XGBoost is a popular choice in machine learning competitions, utilizing a level-wise tree growth strategy.

### Other Models:

- **Random Forest Regressor:** An ensemble method that uses multiple decision trees. It is more robust than individual decision trees but may not capture complex patterns as effectively as boosting models.
- **Gradient Boosting Regressor:** A general term for models based on gradient boosting techniques. Performance depends on the specific implementation and tuning.
- **Extra Trees Regressor:** A variation of Random Forest that introduces more randomness into the tree-building process, potentially improving performance.
- **AdaBoost Regressor:** A model that adjusts the weights of misclassified data points, focusing more on difficult cases in subsequent iterations.
- **Decision Tree Regressor:** A simple model that splits data based on feature values. While interpretable, it is prone to overfitting.
- **Least Angle Regression, Linear Regression, Ridge Regression, Bayesian Ridge, Lasso Regression, Lasso Least Angle Regression, Huber Regressor, Elastic Net, K Neighbors Regressor, Orthogonal Matching Pursuit, Dummy Regressor:** These are various regression models, each with strengths and weaknesses. For instance, Ridge and Lasso are regularized models that prevent overfitting.

## 📄 License

This project is licensed under the [Unlicense](https://unlicense.org/) license. See the `LICENSE` file for more details.

---

This `README.md` file provides an overview of the project, how to set it up, and model evaluation results. For more detailed information and updates, check out the [original repo](https://github.com/haydarkadioglu/btk-datathon24).
```

Feel free to copy and paste this into your `README.md` file!
