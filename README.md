# 🍷 Wine Clustering with PCA and KMeans

This project explores unsupervised learning techniques to cluster different wines based on their chemical properties. Using Principal Component Analysis (PCA) for dimensionality reduction and KMeans for clustering, we reveal hidden patterns and groupings in the wine dataset.

## 📊 Features

- ✅ Data preprocessing and scaling
- ✅ Missing value handling (if any)
- ✅ Dimensionality reduction using PCA
- ✅ Clustering with KMeans
- ✅ 2D visualization of wine clusters

## 📁 Dataset

The project uses the [UCI Wine Dataset](https://archive.ics.uci.edu/ml/datasets/wine) which includes 13 features for different wine samples such as:

- Alcohol
- Malic acid
- Ash
- Flavanoids
- Color intensity
- Proline
- And more...

> Make sure the dataset is saved as `wine.csv` in the root directory. You can also load it directly using `sklearn.datasets.load_wine()`.

## 🚀 How to Run

1. **Clone the repo:**
```bash
git clone https://github.com/YOUR-USERNAME/wine-clustering.git
cd wine-clustering

    Install dependencies:

pip install -r requirements.txt

    Run the script:

python wine_clustering.py

📦 Output

    A CSV file with wine samples and assigned cluster labels

    A 2D PCA scatter plot visualizing the clusters

📈 Sample Plot

<!-- Add your plot image here -->
🧠 Techniques Used

    Imputation: Filling in missing values (if applicable)

    Standardization: Normalizing feature scales

    PCA: Reducing 13 features to 2 for visualization

    KMeans: Grouping wines into clusters based on similarity

🛠️ Requirements

    pandas

    numpy

    scikit-learn

    matplotlib

    seaborn

Install them all with:

pip install pandas numpy scikit-learn matplotlib seaborn

🤝 Contributing

Feel free to fork the repo, open issues, or submit pull requests to enhance this project!
📄 License

This project is licensed under the MIT License.
Made with ❤️ and a touch of wine science by Aman Chaurasia
