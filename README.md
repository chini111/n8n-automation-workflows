# Chest X-Ray Classification - COVID-19, Normal, Pneumonia

I built this as part of my AI Engineering mentorship. The model takes a chest X-ray image and classifies it as COVID-19, Normal, or Pneumonia.

It hit 96% top-1 accuracy over 20 epochs. The more interesting number is the confusion matrix - COVID-19 achieved 1.00 precision despite having the fewest training images, which shows the model actually learned the patterns rather than just defaulting to the most common class.

## What I used

- Python and Google Colab for training
- YOLO11n-cls via the Ultralytics framework
- Chest X-ray dataset from Kaggle (3 classes, labelled)

## Results

- Top-1 accuracy: ~96%
- COVID-19 precision: 1.00 (77 validation images)
- Normal precision: 0.96
- Pneumonia precision: 0.98
- Trained over 20 epochs, no clear signs of overfitting

## Links

- [Colab Notebook](https://colab.research.google.com/drive/1Kbaf7P0b94fOyVIW4huv_XnQ8aGe8sKk)
- [Dataset on Kaggle](https://www.kaggle.com/datasets/prashant268/chest-xray-covid19-pneumonia)
