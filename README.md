# Morphological Classification of Galaxies Using AI

This project leverages a Convolutional Neural Network (CNN) with a modified LeNet-5 architecture to classify galaxies into four major morphological groups: Elliptical, Spiral, Edge-on Spiral, and Irregular. Utilizing datasets from Galaxy10 and the Galaxy Zoo on Kaggle, this model aims to enhance the understanding of galaxies' physical composition and evolutionary traits.

## Project Overview

Galaxies are vast and come in various shapes and sizes, from beautiful spirals to enormous ellipticals. This project uses deep learning to automate the classification of galaxies, aiding in astronomical research and providing deeper insights into our universe's formation and evolution.

### Model Details

- **CNN Architecture**: Modified LeNet-5 - https://alexlenail.me/NN-SVG/LeNet.html
- **Dataset Used**:
  - Training and validation: [Galaxy10](https://astro.utoronto.ca/~hleung/shared/Galaxy10/Galaxy10_DECals.h5)
  - Testing and real-world predictions: [Galaxy Zoo from Kaggle](https://www.kaggle.com/c/galaxy-zoo-the-galaxy-challenge/data)

### Performance

- **Training Accuracy**: 89.83%
- **Testing Accuracy**: 70.66%
- The model successfully predicts the morphological class of unclassified galaxies, showcasing its robustness and accuracy.

## Getting Started

### Prerequisites

- Python 3.8+
- Libraries: TensorFlow, NumPy, Pandas, Matplotlib 

## Contact
- Mehul Paithane - mehul18@iiserb.ac.in
- Yuvraj Sharma - yuvraj19@iiserb.ac.in
- Yatharth Pal - yatharth19@iiserb.ac.in

## Acknowledgements
- Galaxy Zoo for providing a platform and dataset for galaxy classification.
 - The developers of the LeNet architecture for inspiring our CNN model design.
