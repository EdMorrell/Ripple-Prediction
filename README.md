# Ripple-Prediction
Use an LSTM to predict onset of sharp-wave ripple

## Code
1. **Generate_Dataset.ipynb**: Used to create LFP_Seg.pkl file (a labelled dataset of 300ms LFP segments preceding ripple/no ripple segments with labels: 1 - Segment precedes sharp-wave ripple; 0 - Semgent does not precede sharp-wave ripple)

    * To generate LFP_Seg.pkl from scratch must have downloaded files 'AX_Post_Sleep.mat' and have in directory
    
        * Each .mat file is a series of ripple times previously generated in Matlab
        
2. **RNN_Rip_Predict.ipynb**: Jupyter Notebook to build different varieties of LSTM/RNNs to predict onset of sharp-wave ripple

## Requirements
1. Tensorflow (+Keras)
