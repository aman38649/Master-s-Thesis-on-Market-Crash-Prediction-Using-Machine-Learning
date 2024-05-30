# Master-s-Thesis-on-Market-Crash-Prediction-Using-Machine-Learning

## Repository Structure

This repository contains all the necessary data files, code notebooks, and the final thesis document for the project "Market Crash Prediction using Machine Learning".

### Data Files

- **Data Files**: This directory contains the historical index data of 10 different nations, including:
  - S&P 500 (USA)
  - Sensex (India)
  - Hang Seng (Hong Kong)
  - And other international market indices.

### Code Notebooks

- **Code Notebooks**: This directory is divided into two main folders:
  - **Helper Functions**: Contains utility functions used across various models and analyses.
  - **Models**: Contains implementations of five different machine learning models for market crash prediction:
    - Linear Regression
    - Logistic Regression
    - Support Vector Machine (SVM)
    - Decision Trees
    - Recurrent Neural Network (RNN) Long Short-Term Memory (LSTM)

  Additionally, this directory includes three key files:
  - **Analyzing Bull & Bear Market Cycles**: A Python notebook using S&P 500 index market data to analyze bull and bear market cycles.
  - **Index Data Collection**: A Python script for collecting and preprocessing index data.
  - **Exploratory Data Analysis (EDA)**: A Python notebook for performing exploratory data analysis on the collected index data.

### Thesis Document

- **Masters Thesis**: The final thesis document in PDF format, detailing the research, methodologies, results, and conclusions of the project.

## Getting Started

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/yourusername/market-crash-prediction.git
   ```
2. **Navigate to the Repository Directory**:
   ```sh
   cd market-crash-prediction
   ```

3. **Data Files**:
   - Ensure you have the required data files in the `Data Files` directory. If not, follow the instructions in the `Index Data Collection` notebook to download and preprocess the data.

4. **Code Notebooks**:
   - Run the notebooks in the `Helper Functions` directory to load and understand the utility functions.
   - Explore and execute the models in the `Models` directory to train and evaluate different machine learning models for market crash prediction.
   - Review the additional files (`Analyzing Bull & Bear Market Cycles`, `Index Data Collection`, and `Exploratory Data Analysis`) to understand the data collection, preprocessing, and initial analysis steps.

5. **Masters Thesis**:
   - Refer to the `Masters Thesis.pdf` file for a comprehensive understanding of the project, including the theoretical background, methodology, experimental results, and conclusions.

## Requirements

- Python 3.x
- Jupyter Notebook
- Required Python libraries (listed in each notebook's import section)

## Usage

1. **Data Collection and Preprocessing**:
   - Run the `Index Data Collection` Python file to collect and preprocess index data.

2. **Exploratory Data Analysis**:
   - Use the `Exploratory Data Analysis` notebook to perform initial analysis and visualization of the data.

3. **Model Training and Evaluation**:
   - Navigate to the `Models` folder and run the notebooks to train and evaluate the different machine learning models (Linear Regression, Logistic Regression, SVM, Decision Trees, RNN LSTM).

4. **Market Cycle Analysis**:
   - Explore the `Analyzing Bull & Bear Market Cycles` notebook to understand the behavior of market cycles using the S&P 500 index data.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Contact

For any questions or further information, please contact Aman Jain at aman38649@gmail.com.
