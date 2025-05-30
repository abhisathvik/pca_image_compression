# PCA Image Compression

This project demonstrates how Principal Component Analysis (PCA) can be used to compress and reconstruct images. PCA is a powerful dimensionality reduction technique that helps in reducing the storage and computational cost of image data while preserving its essential features.

## 📁 Project Structure

```
.
├── pca_image_compression.ipynb  # Jupyter notebook containing code and explanations
├── README.md                    # Project documentation
└── sample.png                   # (Optional) Folder to store sample input/output images
```

## 🚀 Features

- Load and visualize image data
- Convert color images to grayscale
- Apply PCA for dimensionality reduction
- Reconstruct images from reduced components
- Compare original and compressed images
- Evaluate compression quality visually

## 🛠️ Requirements

Make sure you have the following Python libraries installed:

- numpy
- matplotlib
- scikit-learn
- PIL or OpenCV (optional for image loading)

You can install the required packages using:

```bash
pip install numpy matplotlib scikit-learn pillow
```

## 📓 How to Use

1. Open the `pca_image_compression.ipynb` notebook using Jupyter.
2. Run the cells sequentially to:
   - Load and display the original image.
   - Apply PCA with a specified number of components.
   - Reconstruct and display the compressed image.
   - Optionally adjust the number of components for varying compression quality.

## 🖼️ Example

The notebook includes examples showing:
- The original grayscale image.
- The reconstructed image using various levels of PCA compression (e.g., 10, 50, 100 components).

## 📊 Compression Results

| Components | Description                      |
|------------|----------------------------------|
| 10         | Very high compression, low quality |
| 50         | Balanced compression and quality   |
| 100        | High quality, low compression      |

## 📘 References

- [PCA documentation - Scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html)
- [Image compression using PCA - Towards Data Science](https://towardsdatascience.com/image-compression-using-pca-29f37211e9ed)

## 📄 License

This project is licensed under the MIT License.
