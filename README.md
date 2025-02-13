# Network Intrusion Detection

This repository contains the implementation of a network intrusion detection system using state-of-the-art and hybrid GNNs.

## Datasets

The following datasets were used in this project:

1. **NSL-KDD**: A dataset that improves upon the KDD Cup 1999 dataset, containing various network traffic features and attack types.
   - [NSL-KDD Dataset](https://www.kaggle.com/datasets/hassan06/nslkdd)

2. **UNSW-NB15**: A comprehensive dataset with a wide range of modern attack types and normal network traffic.
   - [UNSW-NB15 Dataset](https://www.kaggle.com/datasets/mrwellsdavid/unsw-nb15)

3. **CICIDS2017**: A dataset that includes various network traffic data with different types of attacks.
   - [CICIDS2017 Dataset](https://www.kaggle.com/datasets/chethuhn/network-intrusion-dataset)

4. **KDD Cup 1999**: A classic dataset used for intrusion detection, containing a large amount of network traffic data.
   - [KDD Cup 1999 Dataset](https://www.kaggle.com/datasets/galaxyh/kdd-cup-1999-data)

## Approach

The project follows a structured approach to build and evaluate GNN-based network intrusion detection models


## Requirements

To run the code in this repository, you need the following Python libraries:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- xgboost
- torch_geometric
- torch 


## Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Abrar2652/network-intrusion-detection.git
   cd network-intrusion-detection
   ```

2. **Download the datasets**:
   - Download the datasets from the provided links and place them in the `data` directory.

3. **Run the Jupyter Notebook**:
   - Open the Jupyter Notebook `network-intrusion-detection.ipynb` and run the cells to preprocess the data, train the models, and evaluate the results.


## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

## License

This project is licensed under the MIT License.

## Acknowledgments

- The authors of the NSL-KDD, UNSW-NB15, CICIDS2017, and KDD Cup 1999 datasets for providing valuable data for research.
- The open-source community for providing tools and libraries that made this project possible.
