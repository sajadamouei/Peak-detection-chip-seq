# ML-Peaks: Chip-seq peak detection pipeline using machine learning techniques
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sajadamouei/Peak-detection-chip-seq/blob/main/ML_Peaks.ipynb "Click to open in Colab") 

[Experiments results](https://docs.google.com/document/d/1lIr_GnLKK7Y9vTBghdIdan7MfagC9UcxQdwh7tA_ROE/edit?usp=sharing) | [Data](https://archive.ics.uci.edu/ml/datasets/chipseq) | [Decoded Data](https://drive.google.com/file/d/1N2PCF3A9atH9lPEVJcBks1HUSFKUZDQ9/view?usp=sharing) | [3D plot of data](https://colab.research.google.com/drive/1pugELPWn2pGpLwHhjAVxUQ13aTWvKHh-?usp=sharing)

### Abstract
We propose a data preprocessing approach using sliding window and feature reduction techniques, and the resulting features can be further used in machine learning methods. Our machine learning methodology can accurately identify peaks using a small training set, which represents a distinct advantage over commonly used statistical approaches, as it has a greater capacity for learning from data. 
 
 We tested our methodology on the H3K9me3_TDH_BP ChIP-seq dataset exploring a range of different machine learning methods, sliding window settings, and feature reduction techniques to detect peak values without human intervention. Our pipeline efficiently detected the peaks, and achieved an F1-score of 0.9644 and a false positive rate of 0.1030.

### Requirements
*Python version 3.8
*scikit-learn
*numpy
*matplotlib
*seaborn
