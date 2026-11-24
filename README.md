# AI Notebooks

My Google Colab notebooks from AI 410 (deep learning), AI 300 (machine learning) and AI competitions, 2026.

Each course folder is split into `finished` (at least one part runs all the way through and works) and `not-finished` (drafts, notes or code with errors).

## AI 410 – Deep learning

**Finished**
- `ResNet_CNN_on_MNIST`: ResNet CNN trained on MNIST, about 96–99% accuracy
- `Batch_Norm_own_layer`: my own batch-norm layer, matches PyTorch's
- `Cross_Entropy_Loss`: my own cross-entropy loss, matches PyTorch's in 1–4 dimensions
- `Assignment_1_Hand-built_MLPs` and `Lecture_1_Hand-built_MLPs_in_class`: hand-built networks for AND, OR, NOT, triangle and K-range
- `Activation_Functions_and_Embedding_PyTorch`: my own activations and embedding, checked against PyTorch
- `NumPy_Neural_Network_with_Adam_*`: neural network and Adam optimizer from scratch in NumPy, about 0.99 F1 on MNIST
- `PyTorch_MLP_*`: MLP trained in PyTorch
- `Dropout_*` and `Full_NN_with_Dropout_on_MNIST`: my own dropout layer in a trained network
- `Small_Language_Model_*`: word-level language model trained on TinyStories (best: 44% accuracy)
- `Image_Preprocessing_*`: image transforms on the Oxford-IIIT Pet dataset
- `Linear_vs_Conv1d`: shows a linear layer and a 1×1 conv1d give the same result

**Not finished:** pooling/conv layer, VGG feature extraction, gradient descent, name generator, drafts

## AI 300 – Machine learning

**Finished**
- `Lecture_3_Scalers_and_Encoders` and `Data_Preprocessing`: min-max and z-score scalers, label and one-hot encoders, all matching scikit-learn
- `K-Nearest_Neighbors_Iris`: k-nearest neighbors on the Iris dataset
- `Linear_Regression`: linear regression with the closed-form solution and with gradient descent
- `NumPy_Neural_Network_digits`: neural network from scratch, about 95% on the digits dataset

**Not finished:** Naive Bayes notes, ridge regression, polynomial fitting, drafts

## AICC (competitions)
- `Smart_Cargo_finished`: delivery-time prediction with linear regression and gradient descent, plus the submission file
- `NEOAI_2025_Cluster_Pictures`: clusters images that were split into pairs of matrices, by rebuilding them, embedding with a pretrained TinyViT and running my own k-means (Kaggle late-submission score 0.086)
- `Simulate_OJIA_1`, `Cybersecurity_AI`, `USAAIO_Breast_Cancer`: started

## Other
Linear algebra (Gram-Schmidt/QR, Hilbert matrices, LU), a Connect Four game and scratch tests.
