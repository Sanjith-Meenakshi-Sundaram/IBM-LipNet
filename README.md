# IBM-LipNet
## Abstract:
LipNet: Visual Speech Recognition Using Deep Learning
LipNet is a deep learning model designed for visual speech recognition by focusing on lip movements to transcribe spoken words from video sequences. It combines Convolutional Neural Networks (CNNs) for spatial feature extraction and Recurrent Neural Networks (RNNs) for temporal sequence modeling. This approach allows the model to track lip movements over time and generate accurate transcriptions, without relying on audio input.

## Overview:

![ibm centre](https://github.com/user-attachments/assets/0127ef12-d537-4e68-ac4a-681a11485a4b)

LipNet leverages both CNNs and RNNs in an end-to-end model for visual speech recognition. It processes video sequences and transcribes lip movements into text without the need for audio signals. This has numerous potential applications in accessibility and voice recognition technologies.

## Features:
End-to-End Model: No need for manual alignment or pre-processing of video data.
Spatial and Temporal Processing: Uses CNNs for spatial feature extraction and RNNs to model temporal sequences.
Visual Speech Recognition: Works solely from lip movements, making it ideal for noisy environments or silent video input.

## Dataset:
LipNet was originally trained on the GRID Corpus, which is publicly available and widely used for visual speech recognition research. You can either download the dataset and preprocess it or use your own dataset of lip movements and corresponding text.

## Output:

![ibm output](https://github.com/user-attachments/assets/f2eccb8a-73f0-4dda-82f2-67065a724b72)

## Applications:
LipNet has promising applications in several areas:

1)Accessibility for the Deaf and Hard of Hearing: Improves communication by providing visual-based speech transcription.
2)Voice Recognition in Noisy Environments: Functions without reliance on audio, making it ideal for use in loud settings.
3)Security and Surveillance: Can be used for silent speech recognition in security footage.

## Result:

![ibm final word](https://github.com/user-attachments/assets/88fcc394-63bd-4af9-a7bf-c0f8f9756a5c)

After running the LipNet model on the video sequence, the final output is the accurate transcription of spoken words based solely on lip movements. The transcribed text is shown in the image above.

