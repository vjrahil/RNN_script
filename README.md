# Script-Generator
Introduction In this project, you'll generate your own Seinfeld TV scripts using RNNs. You'll be using a Seinfeld dataset of scripts from 9 seasons. The Neural Network you'll build will generate a new, "fake" TV script.

## Hyperparameters
**Data Parameter**
   * **Sequence length** = 10
   * **Batch Size** = 128
   
**Training Parameter**
  * **Epochs** = 30
  * **Learning Rate** = .001
  * **Embedding Dimension** = 200
  * **Hidden Dimension in LSTM** = 250
  * **n_layers(Number of RNN layers)** = 2 
  * **Optimizer** = Adam
## Project Information
* Clone the directory by using this command.
``` 
      git clone https://github.com/vjrahil/Script-Generator
```
* All the code is available inside **dlnd_tv_script_generation.ipynb**.

* The preprocessed text is saved in  **preprocess.p**.
* RNN model is saved in **trained_rnn.pt**.

* Generated *fake* TV-Script is saved in **generated_script1.txt**.
