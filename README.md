# Estimate-cetane-number-of-Diesel-fuel
This dataset is to see whether it is possible or not to estimate the cetane number for diesel fuel from the near infrared spectrum for the fuel. There is a total of 245 observations. You receive 133 of these for training and validation, and 112 are kept for testing. You are given the file cnDieselTrain.mat, which contains three matrices: cn-TrainX (401 × 133), cnTrainY (1 × 133), and cnTestX (401 × 112). The first matrix (cnTrainX) contains the IR-spectrum for each sample, one column per sample. The second matrix (cnTrainY) contains the output value cetane number for each diesel fuel. The third matrix (cnTestX) contains the input (IR-spectra) for each sample in the test data set. The spectrum has 401 channels (features), and the data must first be reduced in dimensionality, e.g. by transforming to a principal component basis (which is how it is done in the commercial application) or by selecting appropriate features.
# Methodology:
➢ Python (lib)
➢ Sklearn (lib)
➢ Pandas
➢ Loading the data
➢ PCA (Visualization)
➢ Feature selection
➢ Stand Scaler
➢ Cross validation
➢ Train test split
➢ KNN (Regression)
➢ Random Forest Regressor
➢ Support Vector Machine
➢ Hyper parameter tuning
➢ Evaluating the best model
