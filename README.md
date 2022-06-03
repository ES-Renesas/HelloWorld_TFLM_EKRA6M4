# Porting of Tensorflow lite for microcontrollers on Renesas evaluation kit.

The following repository provides the code used to port [Tensorflow Lite for Microcontrollers](https://www.tensorflow.org/lite/microcontrollers) on to Renesas RA family board, specifically the [EK-RA6M4](https://www.renesas.com/us/en/products/microcontrollers-microprocessors/ra-cortex-m-mcus/ek-ra6m4-evaluation-kit-ra6m4-mcu-group) board. 

The code executes the [Hello World project](https://github.com/tensorflow/tflite-micro/tree/main/tensorflow/lite/micro/examples/hello_world) and outputs the results through UART onto a serial monitor using TFLM reference kernels. 

The project has been developed and tested with e2 studio with flexible software package 3.4, Renesas's tool package that enables easier and faster method to develop the application code.

