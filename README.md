# Neural_Style_Transfer
## Credits
An implementation of neural style transfer, the basic iterative approach and a more advanced approach using AdaIN (Adaptive Instance Normalization). The AdaIN implementation done here takes lots of inspiration (and knowledge and code) from [the unofficial pytorch implementation of the paper](https://github.com/naoto0804/pytorch-AdaIN/tree/master?tab=readme-ov-file).

## Requirements
- Python 
- Pytorch and TorchVision
- PIL
- tqdm and Tensorboard (You could do without these, but having them makes running training files less of a hassle for you)

## Usage
To run the iterative approach, just run the python file on the terminal and provide the FULL path_name of the content and style images you want passed to the model.

For testing the AdaIN approach, run the Testing with UI jupyter notebook, and ensure that the files in Requisite_python_files_for_AdaIN folder are in the same folder as the notebook. After running, the UI asks for input images that you can submit, and we get our output. To test the different decoders, change the decoder_path variable in the notebook to whichever one you would like to use.
