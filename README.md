# 🤗 Hugging Face LLM Course Practical Exercise

This repository contains a comprehensive practical exercise covering Chapters 1-4 of the Hugging Face LLM course, with a **corrected version** that fixes common dataset sampling issues.

## 📚 Exercise Overview

**Goal**: Train and Share Your First Transformer

By completing this exercise, you will apply the concepts from Chapters 1–4:

- **Chapter 1-2**: Use pretrained Transformer models for text classification
- **Chapter 3**: Fine-tune models on custom datasets  
- **Chapter 4**: Share models publicly on the Hugging Face Hub

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab
- Hugging Face account (for sharing models)

### Installation

1. **Clone this repository:**
   ```bash
   git clone https://github.com/sebastiancaraballo/transformers.git
   cd transformers
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Start Jupyter:**
   ```bash
   jupyter notebook
   ```

4. **Open the CORRECTED notebook:**
   - Open `huggingface_practical_exercise_corrected.ipynb` ⭐
   - Follow the step-by-step instructions

## 📖 What You'll Learn

### 🔹 Chapter 1-2: Using Pretrained Models
- Load sentiment analysis models with the `pipeline` API
- Make predictions on custom text
- Understand model confidence scores

### 🔹 Chapter 3: Fine-tuning Models
- Load and prepare the IMDb dataset with **balanced sampling**
- Tokenize text data
- Fine-tune DistilBERT for sentiment analysis
- Evaluate model performance
- **Debug common training issues**

### 🔹 Chapter 4: Sharing on the Hub
- Save models locally
- Push models to Hugging Face Hub
- Make your model publicly available

## 🎯 Expected Outcomes

After completing this exercise, you will have:
- A **properly functioning** fine-tuned sentiment analysis model
- Experience with the complete ML workflow
- A published model on Hugging Face Hub
- Practical knowledge of transformer architectures
- **Understanding of common pitfalls and how to avoid them**

## 📁 Repository Structure

```
transformers/
├── huggingface_practical_exercise_corrected.ipynb  # ✅ RECOMMENDED - Fixed version
├── huggingface_practical_exercise.ipynb            # ⚠️ Original version (has issues)
├── requirements.txt                                 # Python dependencies
├── README.md                                       # This file
├── my-fine-tuned-sentiment-model/                  # Saved model (if you run the exercise)
├── results/                                        # Training results (if you run the exercise)
└── .gitignore                                     # Git ignore file
```

## 🔧 Customization

Feel free to modify the exercise:
- Change the dataset (try other text classification tasks)
- Experiment with different model architectures
- Adjust training parameters
- Use different evaluation metrics

## 🐛 Common Issues and Solutions

### Issue: Model predicts everything as the same class
**Solution**: Check dataset balance and label mapping

### Issue: 100% accuracy on evaluation
**Solution**: Usually indicates overfitting or dataset issues

### Issue: Poor performance
**Solution**: Try more training data or different hyperparameters

### Issue: Label mismatch
**Solution**: Ensure your model's label mapping matches the dataset

## 📚 Additional Resources

- [Hugging Face Course](https://huggingface.co/course)
- [Transformers Documentation](https://huggingface.co/docs/transformers/)
- [Datasets Documentation](https://huggingface.co/docs/datasets/)
- [Model Hub](https://huggingface.co/models)

## 🤝 Contributing

Feel free to submit issues, feature requests, or pull requests to improve this exercise!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Happy Learning! 🎉**

*Remember: Always use the corrected notebook for the best experience!*
