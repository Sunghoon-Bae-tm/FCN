# FCN
Tensorflow implementation of [https://github.com/PacktPublishing/Hands-On-Computer-Vision-with-TensorFlow-2/tree/master/Chapter06] It was trained on the Cityscapes dataset.

## Requirements
1. Tensorflow
2. numpy
3. Matplotlib

## Additional Files
1. cityscapes_utils.py: utility functions for the Cityscapes dataset 
2. keras_custom_callbacks.py: custom Keras callbacks to monitor the trainings of models 
3. mnist_utils.py: utility functions for the MNIST dataset, using tensorflow-datasets 
4. plot_utils.py: utility functions to display results
5. tf_losses_and_metrics.py: custom losses and metrics to train/evalute CNNs
6. tf_math.py: custom mathematical functions reused in other scripts




## Cityscapes datasets
1. Need to download gtCoarse, gtFine, LeftImg8bit, LeftImg8bit_blurred (https://www.cityscapes-dataset.com/)
2. Dataset file path
* cityscapesScripts-master
  - datasets
    + cityscapes
      - gtCoarse
      - gtFine
      - leftImg8bit
      - leftImg8bit_blurred

## FCN architecture
![fcn](https://user-images.githubusercontent.com/75243173/168417856-6ec62a8f-b9d7-45f2-a3d3-085c41c92efc.png)

