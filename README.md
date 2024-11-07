# Neural Collaborative Filtering (NCF) for Movie Recommendation

This repository implements a **Neural Collaborative Filtering (NCF)** model for movie recommendation using the **MovieLens** dataset. The model predicts user ratings for unseen movies based on user-movie interactions, utilizing deep learning techniques such as embeddings and multi-layer perceptrons (MLP).

## Project Overview

This project aims to predict movie ratings using a deep learning model built with **PyTorch**. The model learns user and movie representations (embeddings) and utilizes them through a neural network architecture to predict ratings. The system is evaluated using metrics like **Mean Squared Error (MSE)**, **Root Mean Squared Error (RMSE)**, **Mean Absolute Error (MAE)**, and accuracy.

### Key Features:
- **Data**: 
  - The MovieLens dataset is used, containing **33,832,162 ratings** for **86,537 movies**.
  - **Training Set**: (27,065,729, 2) — pairs of user and movie ratings.
  - **Test Set**: (6,766,433, 2) — used for model evaluation.
- **Model**: 
  - Implements a **Neural Collaborative Filtering (NCF)** architecture.
  - Embeddings for **users** and **movies** are learned to map these entities to dense vector spaces.
  - The neural network combines these embeddings through a **multi-layer perceptron (MLP)** to predict ratings.
- **Training**: 
  - The model is trained using the **Adam optimizer**, a commonly used optimization method in deep learning for its adaptive learning rate capabilities.
  - **Mixed-precision training** is employed for faster training and reduced memory usage.
  - **Automatic gradient scaling** ensures safe and stable training with mixed precision.
  - **Learning rate scheduling** adjusts the learning rate dynamically during training for better convergence.
- **Metrics**: 
  - The model's performance is tracked using:
    - **MSE Loss**: A measure of the average squared difference between predicted and actual ratings.
    - **RMSE**: The square root of MSE, providing an interpretable error metric.
    - **MAE**: The mean absolute difference between predicted and actual ratings.
    - **Accuracy**: Percentage of predictions that fall within a specified tolerance of the true ratings.
- **Visualization**: 
  - The training process is visualized by plotting **loss curves** for training and validation datasets across epochs.
  - This helps to monitor the learning process and adjust hyperparameters as needed.

## Installation

To run the project, clone this repository and install the required dependencies.

### Clone the repository:

bash
git clone https://github.com/khadijaMadane/NeuralCollaborativeFiltering-MovieRecommendation.git


### Navigate to the project directory:

bash
cd NeuralCollaborativeFiltering-MovieRecommendation


### Install the dependencies:

bash
pip install -r requirements.txt


## Usage

### Data Preparation

The **MovieLens** dataset can be downloaded from [here](https://grouplens.org/datasets/movielens/). Once downloaded, you will need to preprocess the data as described in the `data_preprocessing.py` script.

1. Extract the downloaded dataset.
2. Ensure that the `train.csv` and `test.csv` files are properly formatted for use with the model.
3. The script will split the dataset into training and test sets automatically.




## Contributing

Contributions are welcome! Please feel free to submit a pull request if you have any improvements, bug fixes, or suggestions. If you find any issues, you can also open an issue in the repository.

### Contributors:
- **Basma El Barki**
- **Khadija Ben Madanne**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The **MovieLens dataset** is provided by GroupLens Research at the University of Minnesota.
- Thanks to the authors of the original Neural Collaborative Filtering paper for their contributions to collaborative filtering research.


This README.md file is now complete with all the necessary instructions, project overview, and contributor information. You can copy and paste this into your project's README.md file. Let me know if you need further adjustments!
