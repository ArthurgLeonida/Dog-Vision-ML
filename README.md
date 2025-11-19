# End-to-End Dog Breed Classification 🐕

An end-to-end multi-class image classifier capable of identifying 120 different dog breeds using Transfer Learning.

You can access the notebook with google colab:

<a href="https://colab.research.google.com/drive/1ukulgemKLd8uMpC3apFtm4rK7A9-Chuu?usp=sharing#scrollTo=4UcnB20mNKrj">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## 📊 Results
* **Architecture:** MobileNetV2 (feature extractor) + Custom Dense Head.
* **Training:** Optimized using Adam with Categorical Crossentropy.
* **Performance:** Achieved ~99% training accuracy and ~66% validation accuracy on the initial 1000-image subset.

## 🛠️ Technical Highlights
* **Data Pipeline:** Implemented efficient TensorFlow `BatchDataset` pipelines for GPU acceleration.
* **Experiment Tracking:** utilized TensorBoard callbacks to monitor loss curves and prevent overfitting.
* **Inference Visualization:** Created custom prediction plotting to analyze model confidence levels against ground truth.

<img width="1979" height="993" alt="Preds" src="https://github.com/user-attachments/assets/9d1fd1af-e8bb-4bba-a33c-a3bc5e2f199e" />
