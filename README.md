# Fake News Detection Using Machine Learning

This project focuses on building a machine learning model to detect fake news using natural language processing (NLP) techniques. The model is trained and evaluated using a dataset of labeled news articles.

## Features
- **Data Preprocessing:** Cleaning and vectorizing textual data.
- **Model Training:** Applying machine learning algorithms such as Logistic Regression, Naive Bayes, and more.
- **Evaluation Metrics:** Accuracy, precision, recall, and F1-score for performance assessment.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/fake-news-detection.git
   cd fake-news-detection
   ```

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Dataset
The dataset contains labeled news articles categorized as `FAKE` or `REAL`. Ensure you have the dataset saved in the `data` directory with the following structure:

```
data/
├── True_News.csv
├── Fake_News.csv
```

## Usage

1. Run the Jupyter Notebook to preprocess data, train the model, and evaluate its performance:
   ```bash
   jupyter notebook Fake_News_Detection_Using_ML_Task_1.ipynb
   ```

2. Explore the notebook to:
   - Load and preprocess the dataset.
   - Train various machine learning models.
   - Evaluate and compare model performances.


## Project Structure

```
.
├── data/               # Dataset files
├── Fake_News_Detection_Using_ML_Task_1.ipynb  # Jupyter Notebook
├── requirements.txt    # Python dependencies
├── README.md           # Project documentation
```

## Requirements

- Python 3.7 or above
- Jupyter Notebook
- Libraries: numpy, pandas, scikit-learn, etc. (See `requirements.txt`)

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for any feature requests or bug reports.

## License

This project is licensed under the MIT License. See `LICENSE` for more information.

## Acknowledgments

- Dataset sourced from [Kaggle/Dataset Provider Name](kaggle.com).
- Inspiration and guidance from online tutorials and courses.

---

Feel free to explore and modify the project to suit your needs!
