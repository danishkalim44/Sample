## Car Breakdown Prediction:

The problem involves modelling time series data to predict breakdown.

1. Pre processing:
 
    Feature Selection was done based on variance for each features. 

2. Modelling:

    The approach used to solve this is based on deep learning based modelling algorithm. Since the data is time series, both 1. LSTM 2. 1D CNN were used.
1D CNN (convolutional neural network) achieves better performance.
    Since the data suffers from class imbalance, following were used
    1. Instead of measuring accuracy only, F-Score was also used as validation metric. 
    2. Instead of commonly used cross entropy, [Focal loss was used][1].
 
[1]: https://arxiv.org/pdf/1708.02002.pdf    
 