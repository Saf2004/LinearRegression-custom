## Project Title: Binary Linear Classifier and Linear Regression with Gradient Descent

### Overview:
This project implements a binary linear classifier and performs linear regression using the gradient descent algorithm. Two separate tasks are performed:

1. **Binary Linear Classifier**: The project constructs a binary linear classifier for each class against the rest using the Iris dataset. It utilizes a simple linear regression-based approach with a threshold to classify samples into two classes.

2. **Linear Regression with Gradient Descent**: The project implements linear regression using the gradient descent optimization algorithm. It fits a linear equation to noisy data points generated from a linear function and calculates the mean squared error to evaluate the model's performance.

### Requirements:
- Python 3.x

### Installation and Setup:
1. **Clone the repository or download the project files.**

2. **Navigate to the project directory:**
    ```bash
    cd path_to_your_project_directory
    ```

3. **Create a virtual environment:**
    - For Linux/Mac:
        ```bash
        python3 -m venv venv_name
        ```
    - For Windows:
        ```bash
        python -m venv venv_name
        ```

4. **Activate the virtual environment:**
    - For Linux/Mac:
        ```bash
        source venv_name/bin/activate
        ```
    - For Windows:
        ```bash
        venv_name\Scripts\activate
        ```

5. **Install the required libraries using `requirements.txt`:**
    ```bash
    pip install -r requirements.txt
    ```

6. **Run the project:**
    ```bash
    python main.py
    ```

### Code Structure:
- `main.py`: Main script containing the implementation of binary linear classifier and linear regression with gradient descent.
- `README.md`: This file providing an overview of the project.
- `requirements.txt`: File containing the list of required libraries.

### Binary Linear Classifier:
- The `fit()` function constructs binary linear classifiers for each class against the rest using the Iris dataset.
- The `predict()` function predicts the class label for test data using the constructed classifiers.
- Accuracy scores for each class model are printed.

### Linear Regression with Gradient Descent:
- The project generates noisy data points from a linear function and performs linear regression using gradient descent.
- The `linear_eq()` function defines the linear equation.
- The `mean_squared_error()` function calculates the mean squared error between predicted and true values.
- The `gradient_descent()` function implements the gradient descent optimization algorithm to fit the best line to the data points.
- The best fit line equation and mean squared error are printed.
- A scatter plot with the training data and the best fit line is displayed.

### License:
This project is licensed under the MIT License - see the `LICENSE` file for details.
