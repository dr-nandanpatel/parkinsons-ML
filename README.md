# parkinsons-ML
Detecting Parkinsons Disease with ML from pre-existing datasets

<b><h2>Introduction</h2></b>

There are two datasets within this. The first is in the root folder (parkinsons.data which is included here too) and can be used to detect Parkinsons. The second is within the telemonitoring/ directory and contains UDPR scores for us to predict.

This repo also contains pre-trained models(fine tuned) and so can be directly used for their application!

<b><h2>Approach</h2></b>

Approaches are provided in the Jupyter notebook for this repo (parkinsons_trainmodel.ipynb). Run using jupyter notebook from this repo's root folder in the terminal.
You can find more info on the datasets in UCI's database.([info for Parkinsons detection](https://archive.ics.uci.edu/ml/machine-learning-databases/parkinsons/parkinsons.names))([info for UDPR](https://archive.ics.uci.edu/ml/machine-learning-databases/parkinsons/telemonitoring/parkinsons_updrs.names))

<b><h2>Requirements</h2></b>
- Python 3 (recommend using Anaconda)
- XGBoost (pip install xgboost)
- Keras (pip install keras)
- sklearn (pip install scikit-learn)
- Jupyter (instructions)
- Pandas (pip install pandas)
- NumPy (pip install numpy)
- Tensorflow or another Keras backend (pip install tensorflow or for GPU assuming CUDA and CUDNN already installed and in PATH, pip install tensorflow-gpu)

*Disclaimer*: I don't own or have created these datasets and so, I personally should not be held liable for any discrepancies arising in the results or datasets. Also, this repo is created for learning purposeonly so, the resulting asset of the exercise should not be used to provide any kind of healthcare facility to a patient or used in a clinical setting but can be built upon the same (with credits xD) for better and more accurate results!
