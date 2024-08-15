# Anomaly Detection in CICIDS 2017 Dataset Using 4 Different Machine Learning Techniques

This project investigates anomaly detection in network traffic using the CICIDS 2017 dataset. Four different machine learning techniques are applied to identify and classify potential threats and anomalies in the dataset.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Machine Learning Techniques](#machine-learning-techniques)
- [Project Structure](#project-structure)
- [Results and Evaluation](#results-and-evaluation)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

The CICIDS 2017 dataset is a comprehensive dataset that includes various types of network traffic, making it a suitable benchmark for testing anomaly detection algorithms. This project uses four different machine learning techniques to detect anomalies, comparing their performance and effectiveness.

## Features

- **Data Preprocessing:** Cleans and prepares the CICIDS 2017 dataset for analysis.
- **Feature Engineering:** Extracts and selects relevant features for anomaly detection.
- **Multiple Machine Learning Techniques:** Implements four different algorithms to classify network traffic.
- **Performance Evaluation:** Compares the performance of different techniques using metrics like accuracy, precision, recall, and F1-score.

## Technologies Used

- Python
- Scikit-Learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/syedissambukhari/Anomaly-Detection-in-CICIDS-2017-dataset-Using-4-different-Machine-Learning-techniques.git
    ```

2. **Change to the project directory:**

    ```bash
    cd Anomaly-Detection-in-CICIDS-2017-dataset-Using-4-different-Machine-Learning-techniques
    ```

3. **Create a virtual environment (optional but recommended):**

    ```bash
    python -m venv env
    source env/bin/activate  # For Linux and macOS
    env\Scripts\activate  # For Windows
    ```

4. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Run the Jupyter Notebook:**

    - Open the Jupyter Notebook (`supervised and unsupervised machine learning models.ipynb`) in Jupyter.
    - Follow the instructions within the notebook to preprocess data, train models, and evaluate results.

2. **Run the Python script:**

    - Alternatively, run the Python script (`supervised and unsupervised machine learning models.py`) to execute the anomaly detection pipeline.
    
    ```bash
    python supervised and unsupervised machine learning models.py
    ```

## Machine Learning Techniques

The following machine learning techniques are used in this project:

1. **Decision Tree Classifier**
2. **Random Forest Classifier**
3. **Support Vector Machine (SVM)**
4. **K-Nearest Neighbors (KNN)**

## Project Structure

- `Anomaly_Detection.ipynb`: Jupyter Notebook containing the project code and analysis.
- `main.py`: Python script to execute the anomaly detection pipeline.
- `data/`: Directory containing the CICIDS 2017 dataset.
- `models/`: Directory containing trained machine learning models.
- `requirements.txt`: List of required Python packages.
- `README.md`: Project documentation.

## Results and Evaluation

The results and evaluation section provides a detailed comparison of the performance of each machine learning technique, including:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

If you have any questions or suggestions, feel free to contact me.

- **Syed Issam Bukhari**
- [GitHub Profile](https://github.com/syedissambukhari)
- Email: [syedissambukhari33444@gmail.com](mailto:syedissambukhari33444@gmail.com)
