# About The Project

This task is to classify the echoes in leads and sea ice and produce an average echo shape as well as standard deviation for these two classes, Quantify the echo classification against the ESA official classification using a confusion matrix

The tasks in this notebook will be mainly two:

Discrimination of Sea ice and lead based on image classification based on Sentinel-2 optical data.

Discrimination of Sea ice and lead based on altimetry data classification based on Sentinel-3 altimetry data.

## Installation

Below is an example of how you can get the files.

1. Download and register Google Colab at https://colab.research.google.com
2. Select the required file and download it.
3. Open the file and run it.

## Running Tests

To run tests, run the following command

for example, mount the file with google drive

```bash
from google.colab import drive
drive.mount('/content/drive')
```

Plotting the plots
```bash
plt.imshow(labels_image, cmap='viridis')
plt.title('GMM clustering on Sentinel-2 Bands')
plt.colorbar(label='Cluster Label')
plt.show()
```

## Roadmap

- K-means
- Gaussian Mixture Models (GMM)
- Image Classification
- Altimetry Classification
- Some definitions from official ESA document

## Authors

- name: zcfbgub@ucl.ac.uk
- project link: https://colab.research.google.com/drive/1s0jydI2O0YFtUHJ74zLpwWp-OMY0bV-E#scrollTo=oDpD-emQs4wr

## Acknowledgements

- [GitHub Pages](https://pages.github.com)
- [Google Colab](https://colab.research.google.com)


