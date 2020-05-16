DL_from_scratch

Please refer to cnn_demo.ipynb and rnn_demo.ipynb for usage and example. 

## python version
- python3

## python package
- wget
- matplotlib
- numpy
- jupyter
- pandas
- nltk

## Structure of the repository

The structure of this repository is shown as below:

```bash
DL_from_scratch/
	README.md
	data/
		datasets.py     # to load datasets
		mnist.npz         # mnist dataset 
		corpus.csv        # for nltk dataset 
		dictionary.csv  # for nltk dataset
	nn/ 
		operators.py 
		optimizers.py   # SGD, RMSprop, Adam
		layers.py            # layer abstract for CNN and RNN
		loss.py                # loss function for optimization
		model.py           # model abstraction for defining and training models
		initializers.py   # initializing methods for weights and bias
		funtional.py     # some helpful functions
```