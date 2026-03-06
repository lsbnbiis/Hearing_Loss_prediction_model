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
