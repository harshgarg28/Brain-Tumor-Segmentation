# Brain_Tumor_Segmentation
This repository contains the model of spatital attension and the files for segmenting the brain tumor.
this segmentataion involves preproccesing the data and trained using the nvidia-gpu 
this has been trained using batch of 2 and 100 epocs.

![General Flow](/datapreproces.png)


IMPLEMENTATION DETAIL
• The proposed model (dResU-Net with spatial attention) was implemented using Python programming language, Keras library, and TensorFlow as the backend. The proposed model was implemented using Python programming language, Keras library, and TensorFlow as the backend.
• For the experimental purpose, an ADAM optimizer with a learning rate of 0.0001 was used. The activation function
ReLU with batch normalization was employed. Batch normalization normally increases the stability of the model and normalizes the network at each layer.
• The model was trained for 100 epochs on a batch size of 2 due to the limited computational resources. The experiments were conducted on the BraTS 2020 benchmark dataset, from which 75% of the data was used for training, and 25% data for validation.
• The testing was done on 50% of the Brats 2021 benchmark dataset, it was tested for the batch size of 6.