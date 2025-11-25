WM811K Wafer Map Deep Clustering & Relabeling

This project builds a deep clustering pipeline to automatically relabel missing defect labels in the WM-811K wafer map dataset. A convolutional autoencoder learns compact wafer embeddings, followed by KMeans clustering to group similar defect patterns. The system assigns labels to unlabeled wafer maps, producing a fully labeled dataset for downstream supervised defect prediction.



⚠️ Dataset Requirement

This project uses the WM-811K Wafer Map dataset (LSWMD.pkl) from MIT / TSMC.

👉 Users must manually download the dataset and place LSWMD.pkl in the project’s working directory before running any scripts.

Dataset Link (Official):
https://www.kaggle.com/datasets/qingyi/wm-811k-wafer-map

After downloading, ensure that the file LSWMD.pkl is directly located in the same folder as preprocess.py and deepClustering.py.
