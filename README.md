# Credit-Risk-Prediction-MLP-vs.-1D-Tiny-CNN-
Predicts borrower default to support lending decisions using neural models. Trained on **128,396** loans with a **5.4%** default rate; includes end-to-end preprocessing, model comparison, and threshold tuning for operational trade-offs.

**What’s inside**
- Data prep: cleaning, encoding, standardization; stratified train/val/test to handle class imbalance.
- Models: TensorFlow/Keras **MLP** and **1D Tiny-CNN** with regularization & early stopping; selection by ROC-AUC.
- Evaluation: ROC/PR curves, confusion matrices, and business-mode cut-offs.

**Results (test)**
- **MLP ROC-AUC 0.804** (selected); **1D Tiny-CNN AUC 0.700**.
- Operating points: **Recall 94.5% @ thr=0.30**; **F1-optimal P 19.1%, R 41.9% @ thr=0.721**.

**Multilayer perceptron (MLP)**
https://github.com/shaffy-dev/Credit-Risk-Prediction-MLP-vs.-1D-Tiny-CNN-/blob/d482675ec6a320420eb60fb9777815501de095c0/MLP.ipynb

**1D Tiny CNN**
https://github.com/shaffy-dev/Credit-Risk-Prediction-MLP-vs.-1D-Tiny-CNN-/blob/6d3f363bca90fe6a91c2b2aaea8d36c0ca03112f/1D_Tiny_CNN.ipynb
