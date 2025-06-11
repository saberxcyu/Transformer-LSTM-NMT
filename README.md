# Transformer-LSTM-NMT

About 4 months ago I created my first ever repository on GitHub which goes over how to build a simple LSTM neural machine translator for English-Japanese translations. I've since learned a few more advanced techniques on this topic, and have therefore wanted to create this new repo for documenting these amazing things that I've picked up along my path of studying. I also hope that this repository could be used as a studying guide or a stepstone for those out there in the world that are interested or currently trying to learn similar applications.

This repository compares the following architectures for building an NMT:
*  Simple LSTM baseline
*  LSTM with attention mechanism
*  Transformer

It is generally recommended to enjoy the repo in the following manner:
*  First, follow the notebook named "1_Data_Prep" to set up the data needed. (Data are saved on Google Drive)
*  Second, with the data ready on Google Drive, run "2_NMT_with_simple_LSTM" to create a LSTM neural machine translator. (This is similar to my first repo but optimized)
*  Continue with "3_LSTM_with_Attention" to add attention on top and "4_Transformer_NMT" to build a translator using the Transformer architecture.
*  In each notebook, pay attention to how the model is structured. Learn about the architectural differences and compare their performance.

My code follows a consistent structure where all functions are defined at the top with a main function at the bottom for execution. This organization ensures that when the code is run, all commentss and results flow naturally in a clean and structured format that's easy to follow. I genuinely hope these notebooks serve as a useful and enjoyable learning resource. If there are any questions or suggestions, please reach out to me directly on LinkedIn: https://www.linkedin.com/in/saberyu/.
