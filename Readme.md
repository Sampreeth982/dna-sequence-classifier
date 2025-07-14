# 🧬 DNA Sequence Classifier

This project uses a machine learning model to accurately classify DNA sequences as **protein-coding (cDNA)** or **non-coding (ncDNA)**. It leverages 3-mer (trinucleotide) patterns and achieves consistently **high accuracy** on real biological data.

## 🚀 Highlights
- 🔍 Converts DNA into overlapping k-mers (3-mers)
- 🧠 Uses `CountVectorizer` and `LogisticRegression`
- 📊 Delivers **~93% accuracy** with strong precision and recall
- 💡 Ideal for bioinformatics, genetic analysis, and research

## 🧪 Techniques Used
- Bioinformatics preprocessing (k-mer tokenization)
- Machine Learning with Scikit-learn
- Accuracy and classification report for performance evaluation

## 📁 Files Included
- `dna_classifier.ipynb`: Full training + prediction notebook
- (Optional) `vectorizer.pkl`, `model.pkl` for reuse

## 🔧 Requirements
- Python
- Libraries: `pandas`, `scikit-learn`, `numpy`

```bash
pip install pandas scikit-learn numpy
