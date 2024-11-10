# Neural Collaborative Filtering (NCF) for Movie Recommendation

This repository implements a **Neural Collaborative Filtering (NCF)** model for movie recommendation using the **MovieLens** dataset. The model predicts user ratings for unseen movies based on user-movie interactions, utilizing deep learning techniques such as embeddings and multi-layer perceptrons (MLP).

## Project Overview

This project aims to predict movie ratings using a deep learning model built with **PyTorch**. The model learns user and movie representations (embeddings) and utilizes them through a neural network architecture to predict ratings. The system is evaluated using metrics like **Mean Squared Error (MSE)**, **Root Mean Squared Error (RMSE)**, **Mean Absolute Error (MAE)**, and accuracy.

### Dataset:
  - The MovieLens dataset is used, containing **33,832,162 ratings** for **86,537 movies**.
  - **Training Set**: (27,065,729, 2) — pairs of user and movie ratings.
  - **Test Set**: (6,766,433, 2) — used for model evaluation.
The **MovieLens** dataset can be downloaded from [here](https://grouplens.org/datasets/movielens/).

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




## Contributing

Contributions are welcome! Please feel free to submit a pull request if you have any improvements, bug fixes, or suggestions. If you find any issues, you can also open an issue in the repository.

### Contributors:
- **Basma El Barki**
- **Khadija Ben Madanne**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


