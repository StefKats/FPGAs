# FPGAs
FPGAs in cloud computing and machine learning production pipelines

FPGAs can be used in a cluster to host a transformer

They can be connected with GPUs to host larger ML pipelines

Can facilitate high-speed data transfer for distributed training of large-scale machine learning models

Larger NN models can be compressed via quantization aware training, pruning and combining weights to be run with low latency and power consumption 

Compressed NNs can be translated to by HLS4ML to C++. The C++ is given to Vivado to translate into FGPA logic (Hardware description language, such as VHDL). The design is tested and is converted into a bitstream file which is used ro program the FPGA.

Real time inference, edge computing and cloud data centre processing.
