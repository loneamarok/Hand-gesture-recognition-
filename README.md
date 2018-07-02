# Hand-gesture-recognition-
A software that uses ANN and image processing techniques like skin segmentation and Sobel filter to classify hand gestures into 5 types and recognize them.

1. Unzip
2. Open matlab. Put all files and images in current directory.
3. Run NNinputstestskin(100) in terminal of matlab. This trains a neural network for the given 100 images with 1 hidden layer with 20 nodes. You can change the nuber of hidden nodes in the script. You can acquire you own images and train it also.
4. The NNinputstestskin outputs a network "net".
5. Run skinmain(net) to start gesture recognition. It captures and recognizes images every 2 seconds(can be changed).
6. Prerequsites : Webcam, Matlab software.
