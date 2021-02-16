# ECG-Arrhythmia-Classification-in-2D-CNN

This is an implementation based on this paper, **"ECG arrhythmia classification using a 2-D convolutional neural network", Tae Joon Jun et al., CVPR 2018."** with some personal modifications

# **Dataset**

This repo adapts [MIT-BIH Arrhythmia Database](https://physionet.org/physiobank/database/mitdb/) as training and testing dataset.

the script is modified from [MIT-BIH-Arrhythmia-Downloader](https://github.com/lext/MIT-BIH-Arrhythmia-Downloader.git)

## **Data Pre-Process**

To turn ECG signals to images, the script can be found under `/mit_arrhythmua_dat/`

The script will output EIGHT types of heart beats based on the annotations that the officials provide. A heart beat is defined by the peak of R waves
according to the contents on the websites.
