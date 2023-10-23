# GMM Iris Clustering

This project uses a Gaussian Mixture Model (GMM) to perform clustering on the Iris dataset. GMM is a probabilistic model that assumes that the data points are generated from a mixture of several Gaussian distributions. It's a powerful technique for clustering data points.

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn

You can install the required Python packages using pip:

```bash
pip install numpy pandas matplotlib scikit-learn
```

## Project Structure

The project repository will have the following structure:

```
GMM-Iris-Clustering/
│
├── GMMproject.ipynb
│
├── README.md
│
└── data/
    ├── iris.data
```

## How to Run the Project

Follow these steps to run the project:

1. Clone this repository:

   ```bash
   git clone https://github.com/ParthShethSK/GMM-Iris-Clustering.git
   ```

2. Change directory to the project folder:

   ```bash
   cd GMM-Iris-Clustering
   ```

3. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open the `GMMproject.ipynb` notebook using Jupyter Notebook.

5. Follow the instructions in the Jupyter Notebook to run the code cells.

Make sure you have the Iris dataset file (`iris.data`) in the `data/` folder. The notebook (`GMMproject.ipynb`) contains the code for loading the dataset and applying GMM clustering.

## References

- Scikit-Learn Documentation: [Gaussian Mixture Models](https://scikit-learn.org/stable/modules/mixture.html#gaussian-mixture)
- Iris Dataset: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)
