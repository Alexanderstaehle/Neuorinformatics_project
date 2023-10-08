# Detecting Button Presses in EEG Data

This is the repository of a course project in neuroinformatics. The project was about using autoencoder anomaly detection in order to detect button presses in EEG data.

The project was implemented using the ```MNE``` library for the processing of EEG data in python, and ```TensorFlow``` for the autoencoder models.

## Setup

To create an environment with all necessary packages to run the code of this project please refer to the [```requirements.txt```](https://github.com/LukasKarner/neuro-project/blob/main/requirements.txt) file.

## Data

The data used for this project is included in the [```data```](https://github.com/LukasKarner/neuro-project/tree/main/data) directory.

The source of the data is the ["A large electroencephalographic motor imagery dataset for electroencephalographic brain computer interfaces"](https://figshare.com/collections/A_large_electroencephalographic_motor_imagery_dataset_for_electroencephalographic_brain_computer_interfaces/3917698) dataset [1].
There it is necessary to download the files with names NoMT and FreeForm.

[1] Kaya, Murat; Binli, Mustafa Kemal; Ozbay, Erkan; Yanar, Hilmi; Mishchenko, Yuriy (2018). A large electroencephalographic motor imagery dataset for electroencephalographic brain computer interfaces. figshare. Collection. https://doi.org/10.6084/m9.figshare.c.3917698.v1

## Notebooks

The final versions of the modeling pipelines for the (convolutional) autoencoders, including data loading, data preprocessing, data preparation, model training, and model evaluation, can be found in the notebooks [```ae.ipynb```](https://github.com/LukasKarner/neuro-project/blob/main/ae.ipynb) and [```conv_ae.ipynb```](https://github.com/LukasKarner/neuro-project/blob/main/conv_ae.ipynb) respectively.

## Report

The final presentation of this project can be found in [```slides.pdf```](https://github.com/LukasKarner/neuro-project/blob/main/slides.pdf)

![title slide](https://github.com/LukasKarner/neuro-project/blob/main/archive/title.png)