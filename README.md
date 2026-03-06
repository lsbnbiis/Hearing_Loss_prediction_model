The models are built in two versions: with SNP features and without SNP features. If your dataset does not contain SNP information, please run nosnp_prediction.ipynb. If your dataset contains SNP information, please run snp_prediction.ipynb. The program will call the corresponding model to perform early hearing loss prediction.
## 🚀 Usage
Run the jupyter notebook

## ⚙️ Requirements
Install required packages:
- Python
- pandas
- numpy
- jupyter
- matplotlib
- joblib

## 📊 Model
| Model | SNP Feature | Notebook |
|------|------|------|
| Clinical Model | ❌ No | nosnp_prediction.ipynb |
| Genomic Model | ✅ Yes | snp_prediction.ipynb |

Prediction results for females across different models(♀ Female)
| Features/Model | SVM | RF | XGBoost | DecisionTree | HGBC |
|------|------|------|------|------|------|
| Non-SNP | 0.82 | 0.76 | 0.81 | 0.72 | 0.79 |
| TPMI_9 | 0.94 | 0.74 | 0.91 | 0.71 | 0.91 |
| PRS_5 | 0.82 | 0.74 | 0.85 | 0.76 | 0.85 |

Prediction results for males across different models(♂ Male)
| Features/Model | SVM | RF | XGBoost | DecisionTree | HGBC |
|------|------|------|------|------|------|
| Non-SNP | 0.84 | 0.73 | 0.70 | 0.66 | 0.75 |
| TPMI_9 | 0.68 | 0.65 | 0.71 | 0.68 | 0.68 |
| PRS_5 | 0.76 | 0.68 | 0.79 | 0.79 | 0.76 |

## 📊 Prediction Results
The red square indicates that the prediction result is hearing loss, while the green square indicates normal hearing.
🟥 Hearing Loss
🟩 Normal
