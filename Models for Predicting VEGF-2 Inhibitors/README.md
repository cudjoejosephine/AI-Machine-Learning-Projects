In this project, I collaborated on developing regression models to predict the IC50s of inhibitors against VEGFR-2.
This receptor is responsible for regulating the formation of blood vessels.
In malignant tumors, VEGFR-2 is upregulated, triggering the abnormal formation of blood vessels leading to metastasis of cancer cells.
Existing VEGFR-2 drugs are associated with high toxicity and necessitate the discovery of less harmful drugs.
To fastrack the discovery process, this project aimed to develop regression models to predict the IC50s of potential inhibitors.
Bioactivity datasets were downloaded from ChEMBL and were used to train three different models including Artificial Neural Network(ANN), K-Nearest Neighbor(KNN) and Random Forest(RF).
After evaluating these models, the K-Nearest Neighbour model with Morgan Molecular Fingerprints outperformed the other models with an R-squared (R2) score of 0.53 and normalized Mean Absolute Error (MAE) of 0.00569.
The KNN model was then deployed using Streamlit 
