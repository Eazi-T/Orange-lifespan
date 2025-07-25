# Orange-lifespan-prediction

## 🗂️ Lifespan Classes
The images were grouped into the following lifespan categories:

| Class | Days After Harvest |
| ----- | ------------------ |
| 0     | 1–3 days           |
| 1     | 4–6 days           |
| 2     | 7–9 days           |
| 3     | 10–12 days         |
| 4     | 13–15 days         |

## 🧠 Methodology
- Data Collection: Images of oranges taken daily in controlled lighting conditions.
- Data Preprocessing:
- Resizing images
- Normalization
- Data augmentation (rotation, zoom, flip)

## Model Architecture:
- Convolutional Neural Network (CNN)
Layers: Conv2D → MaxPooling → Dropout → Flatten → Dense
Training:
Optimizer: Adam
Loss: Categorical Cross-Entropy
Metrics: Accuracy

## 📌 Conclusion
This model can serve as a base for smart sorting systems in post-harvest fruit processing, enabling automated grading and timely distribution.

