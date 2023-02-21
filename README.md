# DeepLab-V3+ implementation

### Please see presentation for the changes made to the original

## Original project:
--> https://keras.io/examples/vision/deeplabv3_plus/

OR

--> https://github.com/keras-team/keras-io/blob/master/examples/vision/deeplabv3_plus.py

### I've tried to make some changes to the original project to check if i get a better output results.

## Changes Made:-

- Implemented AdamW optimizer instead of Adam
- Epochs changed from 25 to 28
- Activation function used is Leaky Relu
- Increased Batch size from 4 to 8


Achieved accuracy is rather same but reduced in Overfitting to some extent

- Original Accuracy (25 epochs) – 93.77
- Achieve Accuracy 25 epochs – 93.73 (after modifications)
- Achieved Accuracy 28 epochs – 94.16 (after modifications)
