# KNN Voice Gender Recognition

A simple machine learning project that uses the K-Nearest Neighbors (KNN) algorithm to classify voice recordings as male or female based on extracted acoustic features.

## Project Structure

- `dataset/`: Contains the voice dataset in CSV format.
- `knn_voice_gender.ipynb`: Jupyter notebook with all the code for data loading, preprocessing, training, and evaluation.
- `requirements.txt`: Lists the required Python libraries.

## Features

- Loads and preprocesses voice data (feature scaling, encoding).
- Trains a K-Nearest Neighbors model.
- Evaluates model accuracy.
- Allows you to tweak parameters (e.g., number of neighbours) for better performance.

## Tools & Libraries

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib (for optional visualisations)

## How to Use

1. **Clone the repository:**

   ```bash
   git clone https://github.com/nurulashraf/knn-voice-gender-recognition.git
   cd knn-voice-gender-recognition
   ```

2. **Set up your environment:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook:**

Open `knn_voice_gender.ipynb` using Jupyter Notebook or Jupyter Lab and run through the cells step by step.

## License

This project is licensed under the [MIT License](LICENSE).
