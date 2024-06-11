All the required python files.

net.py is a file with the AdaIn network coded in pytorch. The decoder is trainable whereas the vgg-encoder is not. Class Net in the same file is the complete model along with the coding of style and content losses.

The AdaIn 'layer' itself is coded in the function.py file. Details in report.

sampler.py defines an infinite sampler for a PyTorch data loader. It ensures that samples are continuously drawn from the dataset, shuffling the order each time the dataset is exhausted.
