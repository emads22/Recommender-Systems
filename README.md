# Recommendation Systems Exploration

This project contains three Jupyter Notebook files focusing on different recommendation techniques: **Collaborative**, **Content-Based**, and **Popularity-Based** Filtering

## 1. collaborative_based_filtering.ipynb

### Description:
This notebook explores collaborative-based filtering for recommendation systems. It covers the following steps:

- **Introduction to Collaborative-Based Filtering**: Overview of the technique and its goal to predict user preferences based on similar users' preferences.
- **Data Loading**: Loading movie ratings data into a DataFrame.
- **Dataset Creation**: Using Surprise library to create a dataset from the ratings data.
- **Trainset Building**: Building a training set for the collaborative filtering model.
- **Model Training**: Training a Singular Value Decomposition (SVD) model.
- **Prediction**: Making predictions for user ratings.
- **Validation**: Cross-validation to evaluate the model's performance.

## 2. content_based_filtering.ipynb

### Description:
This notebook explores content-based filtering for recommendation systems. It includes the following sections:

- **Data Loading**: Loading movie data and preparing it for analysis.
- **TF-IDF Vectorization**: Converting movie overviews into TF-IDF vectors.
- **Similarity Matrix**: Computing the similarity matrix based on TF-IDF vectors.
- **Similarity Search**: Finding similar movies based on their overviews.

## 3. popularity_based_filtering.ipynb

### Description:
This notebook demonstrates popularity-based filtering for recommendation systems. It covers the following steps:

- **Data Loading**: Loading movie data, credits data, and ratings data.
- **Minimum Votes Calculation**: Determining the minimum number of votes required for consideration.
- **Data Filtering**: Filtering movies based on the minimum vote count.
- **Weighted Rating Calculation**: Calculating the weighted rating for each movie.
- **Sorting and Cleaning Data**: Sorting and cleaning the movie data based on weighted ratings.

Each notebook provides detailed explanations and code implementation for its respective recommendation technique.

## Features:

- Each notebook provides detailed explanations and code implementation for its respective recommendation technique.
- Utilizes popular libraries such as Surprise for collaborative filtering and scikit-learn for content-based filtering.
- Demonstrates different approaches to recommendation systems, including collaborative, content-based, and popularity-based methods.

## Usage:

To use these notebooks, follow these steps:

1. Clone or download this repository to your local machine.
2. Install Anaconda or Miniconda if not already installed. Anaconda can be downloaded from the [Anaconda website](https://www.anaconda.com/products/distribution), and Miniconda can be downloaded from the [Miniconda website](https://docs.conda.io/en/latest/miniconda.html).
3. Create a Conda environment using the provided `environment.yml` file. Run the following command in your terminal or command prompt:

    ```bash
    conda env create -f environment.yml
    ```

   This will create a new Conda environment named `recommendation_systems_env` with all the required packages installed.
4. Activate the Conda environment:

    ```bash
    conda activate recommendation_systems_env
    ```

5. Launch Jupyter Lab:

    ```bash
    jupyter lab
    ```

6. Open the desired notebook from the Jupyter Notebook interface and follow the instructions within each notebook to execute the code and explore the recommendation techniques.

## Contributing

Contributions are welcome! Here are some ways you can contribute to the project:
- Report bugs and issues
- Suggest new features or improvements
- Submit pull requests with bug fixes or enhancements

## Author

- Emad &nbsp; E>
  
  [<img src="https://img.shields.io/badge/GitHub-Profile-blue?logo=github" width="150">](https://github.com/emads22)

## License

This project is licensed under the **MIT License**, which grants permission for free use, modification, distribution, and sublicense of the code, provided that the copyright notice (attributed to [emads22](https://github.com/emads22)) and permission notice are included in all copies or substantial portions of the software. This license is permissive and allows users to utilize the code for both commercial and non-commercial purposes.

Please see the [LICENSE](LICENSE) file for more details.