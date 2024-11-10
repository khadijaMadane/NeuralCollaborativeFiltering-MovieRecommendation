# Neural Collaborative Filtering (NCF) for Movie Recommendation

This repository hosts the implementation of a **Neural Collaborative Filtering (NCF)** model designed for recommending movies, utilizing deep learning techniques with **PyTorch** and the well-known **MovieLens dataset**. The model predicts user ratings for movies they have not yet seen, based on learned user-movie interactions.

## Project Overview

The primary objective of this project is to build a recommendation system that can predict how a user would rate a movie they haven’t yet rated. The model leverages a neural network architecture to capture complex user-movie relationships by learning embeddings for both users and movies. Using these embeddings in a multi-layer perceptron (MLP) framework, the system outputs predicted ratings, aiming to improve recommendation quality.

## Dataset:
  - The MovieLens dataset is used, containing **33,832,162 ratings** for **86,537 movies**.
  - **Training Set**: (27,065,729, 2) — pairs of user and movie ratings.
  - **Test Set**: (6,766,433, 2) — used for model evaluation.
  - The **MovieLens** dataset can be downloaded from [here](https://grouplens.org/datasets/movielens/).

## Installation

To run the project, clone this repository and install the required dependencies.

- #### Clone the repository:

bash
git clone https://github.com/khadijaMadane/NeuralCollaborativeFiltering-MovieRecommendation.git


- #### Navigate to the project directory:

bash
cd NeuralCollaborativeFiltering-MovieRecommendation


- #### Install the dependencies:

bash
pip install -r requirements.txt

## Usage

Once the dependencies are installed, you can start training the model on the MovieLens dataset or your own data. Adjust the hyperparameters and model architecture as desired in the code.


## Contributing

Contributions are welcome! Please feel free to submit a pull request if you have any improvements, bug fixes, or suggestions. If you find any issues, you can also open an issue in the repository.

#### Contributors:
- **Khadija Ben Madanne**
- **Basma El Barki**


## References

1. He, X., Liao, L., Zhang, H., Nie, L., Hu, X., & Chua, T. S. (2017). Neural Collaborative Filtering. Proceedings of the 26th International Conference on World Wide Web (pp. 173–182). 

2. MovieLens Dataset. GroupLens Research. [Link](https://grouplens.org/datasets/movielens/) 

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


