# PotholeDetection

This model is a fine-tuned version of facebook/detr-resnet-50 on the pothole-segmentation dataset found on Hugging Face manot/pothole-segmentation 


Training hyperparameters

The following hyperparameters were used during training:

learning_rate: 1e-05

train_batch_size: 8

eval_batch_size: 8

seed: 42

optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08

lr_scheduler_type: linear

num_epochs: 10


Framework versions

Transformers 4.31.0

Pytorch 2.0.1+cu118

Datasets 2.14.3

Tokenizers 0.13.3
