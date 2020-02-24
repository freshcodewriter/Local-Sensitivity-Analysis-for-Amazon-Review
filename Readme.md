# ESE545-Project1: Amazon Reviews Similarity Analysis

This project analyse the similarity of 180000+ Amazon reviews using Local Sensitivity Hashing with 9 main different functions.

1. data_loader: Load data from JSON file and pre-process data
2. cal_binary_matrix: Convert the text to binary matrix
3. cal_jaccard_distance_randomPairs: Compute the jaccard distance of 10000 random pairs, and plot the histogram
4. hit_pro_with_band: Find the relationship between similarity and probability of hitting under different paramter settings
5. cal_signature_matrix: Find the Min Hashing representation of the binary matrix
6. cal_hash_signature_matrix: Find the Local Sensitivity Hashing representation of the Min Hashing matrix
7. filterPairs: Find the pairs of documents with jaccard distance < 0.2
8. writeToFile: Store the review id and review text of nearest pair into csv
9. findNearestNeighbor: Taking a new review as input and return its nearest neighbor

## Getting Started

### Prerequisites

You need to have <amazonReviews.json> located at the same directory as the main.py

## Running the tests

Run main.py to generate results

## Authors

* **Jiaxiao Cai** *
* **Tejas Srivastava** *
