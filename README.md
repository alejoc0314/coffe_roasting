# Coffee Roasting Predictions with Neural Networks

## Project Overview
This project implements a neural network model to predict coffee roasting characteristics using temperature and duration data. The goal is to develop a model that can accurately predict coffee roast quality based on the temperature and time profiles used during the roasting process.

## Model Architecture
The neural network model consists of two layers:
- **Layer 1**: A Dense layer with 3 output units and Sigmoid activation.
- **Layer 2**: A Dense layer with 1 output unit for binary classification (roast success/failure) using a Sigmoid activation.

### Model Summary:

| Layer (type)    | Output Shape | Param # |
|-----------------|--------------|---------|
| layer_1 (Dense) | (None, 3)    | 9       |
| layer_2 (Dense) | (None, 1)    | 4       |

**Total params**: 13 (52.00 B)  
**Trainable params**: 13 (52.00 B)  
**Non-trainable params**: 0 (0.00 B)
