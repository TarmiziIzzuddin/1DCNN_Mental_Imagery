# Mental Classification using one-dimensional CNN

## Introduction
This repo contains the implementation of the following paper (please cite if you find this useful):


```
@ARTICLE{Izzuddin2021-md,
  title     = "Mental imagery classification using one-dimensional
               convolutional neural network for target selection in
               single-channel {BCI-controlled} mobile robot",
  author    = "Izzuddin, Tarmizi Ahmad and Safri, Norlaili Mat and Othman, Mohd
               Afzan",
  journal   = "Neural Comput. Appl.",
  publisher = "Springer Science and Business Media LLC",
  volume    =  33,
  number    =  11,
  pages     = "6233--6246",
  month     =  jun,
  year      =  2021,
  language  = "en"
}
```

This proposes the use of 1D-CNN to classify the mental imagery signal from EEG data, with an application toward target selection for a teleoperable mobile robot.

<p align="center">
  <img width="522" height="477" src="https://github.com/TarmiziIzzuddin/1DCNN_Mental_Imagery/blob/main/NCAA-Diagram.png">
</p>

## Requirement (tested on)

Python == 3.6
numpy == 1.19.5
tensorflow == 2.5.0 (GPU or CPU)
pandas == 0.23.4


## Running Intruction

Example of running the 1D-CNN classification and visualization of learned kernels are available in the jupyter notebook "1D_CNN_mental_imagery.ipynb"

## Data availability

As data contains private subject's information, please do a personal request should it be required.


