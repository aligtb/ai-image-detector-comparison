# 📓 notebooks/

All our experimentation and model evaluation is done in Jupyter notebooks.

## 📄 Files

- `preprocessing.ipynb` – Resize, normalize, augment images
- `xception_detector.ipynb` – Run inference with XceptionNet (🔖example)
- `evaluation.ipynb` – Accuracy, precision, confusion matrix, etc.

## ✅ Workflow

1. Preprocess images (resize, normalize)
2. Apply each model on dataset
3. Store predictions and scores
4. Evaluate and visualize metrics
5. Save results to `../results/`

## 💡 Tips

- Use GPU in Colab for faster inference.
- Use helper functions to avoid code repetition.
