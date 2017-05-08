# live_mnist
MNIST Live - Run Digit Recognition powered by a Conv Net using live video feed your webcam. The script uses a convolutional neural network in keras plus some adaptive treshholding and contours in open cv.

To run the main script first clone the repo, then create a conda environment with all the dependendencies (this might take a while since the script uses both keras and open cv) and then run the `live_mnist.py` script. It will take a few seconds for the webcam to start.

    git clone https://github.com/apapiu/live_mnist.git
    cd live_mnist

    conda env create -f environment.yml
    python live_mnist.py


There is a basic CNN in this repo that gets loaded automatically using keras in the script - however you can play around with training your own - take a look at the `train_model.py` script for the architecture. It will take around 700 seconds on a Macbook Pro to get over 99% accuracy.
