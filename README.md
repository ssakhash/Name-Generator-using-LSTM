# Name-Generator-using-PyTorch-LSTM
Character-level text generator using LSTM.

Dataset contains 2000 words with atmost 11 characters per word. In the pre-processing stage, OneHot Encoding was performed with 26 alphabets and EON which denotes 'End of Name'. LSTM model was trained using PyTorch while feeding one character at a time in every word followed by EON to denote completion of word. In the pre-processing stage, each word was made 11 characters by using EON as fillers to denote 'End of Name'. Trained model is capable of generating names based on the initial character that is fed to the network.
