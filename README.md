# Model Quantization Examples
This GitHub repository contains two Jupyter notebooks that provide examples for how to quantize a deep learning model using different frameworks.

## PyTorch Quantization Example
The pytorch_quantization_example.ipynb notebook demonstrates how to quantize a pre-trained Timm model using PyTorch's built-in quantization functionality. The notebook includes step-by-step instructions and code for quantizing the model, evaluating the quantized model's performance, and comparing it to the original floating-point model.

## OpenVINO Quantization Example
The openvino_quantization_example.ipynb notebook provides an example of how to quantize a pre-trained GoogleNet model using the Intel OpenVINO Toolkit. The notebook includes step-by-step instructions and code for converting the model to OpenVINO format, quantizing the model using OpenVINO's Post-Training Optimization Tool, and evaluating the quantized model's performance.

### Requirements
PyTorch 1.9.0 or higher
OpenVINO Toolkit 2021.4 or higher
Jupyter Notebook
