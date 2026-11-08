# YESNO Audio Classification Mini-Project

## Project Overview

This project implements binary speech classification using the TorchAudio YESNO dataset as part of a Digital Speech Processing mini-project.

The objective is to classify spoken Yes and No words using MFCC features and four machine learning classifiers.

## Dataset

- Total recordings: 60
- Words per recording: 8
- Total speech samples: 480
- Sampling rate: 8000 Hz
- Classes: No (0) and Yes (1)

## Methodology

1. Audio loading and visualization
2. Speech segmentation and verification
3. MFCC feature extraction
4. Recording-level train/test split
5. SVM classification
6. KNN classification
7. Random Forest classification
8. Neural Network (MLP) classification
9. Model comparison
10. Five-fold group-based cross-validation

## Experimental Results

| Classifier | Test Accuracy | Cross-Validation Accuracy |
|---|---:|---:|
| SVM | 100% | 99.38% |
| KNN | 100% | 99.38% |
| Random Forest | 100% | 99.38% |
| Neural Network (MLP) | 100% | 99.38% |

## Tools and Libraries

Python, PyTorch, TorchAudio, Librosa, Scikit-learn, NumPy, Pandas, and Matplotlib.

## Conclusion

All four classifiers achieved excellent performance on the YESNO dataset using MFCC-based acoustic features.

The results demonstrate the effectiveness of the selected methods on this dataset. However, further evaluation on independent recordings is needed to assess generalization to more diverse speech conditions.
