# STAT-XAI: Statistical Explainability Framework

**STAT-XAI** is a statistical framework designed to explain and rank feature importance in machine learning models using hypothesis testing and effect size analysis.

## 🔍 What This Repository Contains

- 📊 **Models**: MLP, RNN (LSTM), and Transformer
- 🧪 **Datasets**: 6 Synthetic + 3 Real-World datasets
- 📈 **Explanation**: Uses statistical tests (T-test, ANOVA, effect sizes) to validate feature importance
- 📂 **Results**: Ranked feature plots and statistical metrics

## 📁 Directory Structure

- `notebooks/`: Experiments grouped by dataset type
- `datasets/`: Input CSVs
- `results/`: Saved rankings and visualizations
- `utils/`: Reusable preprocessing and statistical functions

## ⚙️ Setup

```bash
pip install -r requirements.txt
