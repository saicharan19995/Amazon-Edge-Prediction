# Amazon Edge Prediction

This project aims to build a recommendation system this is important for companies that have a variety of products or services and want to upsell the customer by recommending some of the related products in which the customer is interested and this also improves customer satisfaction and experience in exploring different similar products. These systems are mainly used by Amazon, Netflix, and Spotify are some of the familiar companies which use recommender systems. These systems work on two different principles one based on past interactions and behaviours and the other based idea of the recommender system is on the history of customers who purchased similar products.

## Prerequisites
Python 3.8 or higher\
TensorFlow 2.6.0 or higher\
StellarGraph library

## Installation

Use the pip install command to install all the requirements specified in the requirements.txt.

```bash
pip3 install -r requirements.txt
```
```bash
pip install -r requirements.txt
```

## Usage
Import the necessary libraries.

Define the dataset path as shown bellow.
``` python
amazon_csv = pd.read_csv("ratings.csv")
```

To run the complete project

```bash
python3 CS286_Project.py
```
To train and visualize each line of code use the .ipynb file

```bash
jupyter notebook
```

Open CS286_Project.ipynb and start running all cells

## Dataset

ratings.csv is the dataset which contains list of all the edges with ratings and time as the other 2 columns.

## Contributors
Sai Charan Goniguntla
