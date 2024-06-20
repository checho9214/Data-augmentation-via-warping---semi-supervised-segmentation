# Data Augmentation via Warping Transforms for Modeling Natural Variability in the Corneal Endothelium Enhances Semi-Supervised Segmentation

Deep learning has made a significant contribution to biomedical image segmentation by automating the delineation process in medical images. To achieve this task, models need to be trained using a large amount of annotated or labeled data that highlights the region of interest with a binary mask. However, efficiently generating annotations for such large datasets requires an expert biomedical analyst and a significant manual effort. It is a tedious and costly task, and also prone to human errors. To address this issue, we propose a semi-supervised learning framework that can be trained with a limited number of annotated samples and a large amount of unlabeled samples, which is common in real-world problems.

This repository includes the implementation of the article "Data Augmentation via Warping Transforms for Modeling Natural Variability in the Corneal Endothelium Enhances Semi-Supervised Segmentation" which can be easily integrated with any Encoder-Decoder model.

## Features

The code for this research offers the following features:

1. Extract the encoder part and convert it to Siamese-Net for pre-training with Barlow Twins.
2. Integration of the pre-trained encoder with the encoder-decoder model for fine-tuning.
3. Evaluation with standard metrics for segmentation tasks.
4. Output visualization.
5. A Jupyter Notebook using different data augmentation strategies.

## Requirements

- Python 3.x
- Required libraries:
  - numpy
  - matplotlib
  - scikit-image
  - opencv-python
  - tensorflow / pytorch (depending on the model implementation)

## Citation

```bibtex
@article{Sanchez2024bt,
  title={Data augmentation via warping transforms for modeling natural variability in the corneal endothelium enhances semi-supervised segmentation},
  author={Sergio Sanchez, Noelia Vallez, Gloria Bueno, Andres G. Marrugo},
  journal={Deep Learning},
  pages={1--29},
  year={2024},
  publisher={PLOS ONE}
}

