# Ripple-Prediction
Use an LSTM to predict onset of sharp-wave ripple

1. Generate_Dataset used to create LFP_Seg.pkl file (a labelled dataset of 300ms LFP segments preceding ripple/no ripple segments)

    * To generate LFP_Seg.pkl from scratch must have downloaded files 'AX_Post_Sleep.mat' and have in directory
    
        * Each .mat file is a series of ripple times previously generated in Matlab
        
2. RNN_Rip_Predict: Jupyter Notebook to build different varieties of LSTM/RNNs to predict onset of sharp-wave ripple
