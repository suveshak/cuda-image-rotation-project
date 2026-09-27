# CUDA at Scale - GPU Image Rotation

This project performs image rotation using a custom CUDA kernel on an NVIDIA GPU.

## Project Description

The program reads 100 grayscale PGM images, transfers each image to GPU memory, performs 90-degree rotation using a CUDA kernel, transfers the result back to the CPU, and saves the rotated images.

## GPU Processing

- GPU: NVIDIA Tesla T4
- CUDA: CUDA 12.8 compiler
- Input images: 100
- Output images: 100
- Processing: CUDA GPU kernel
- Image format: PGM grayscale

## Execution

The program was compiled and executed in Google Colab using the NVIDIA Tesla T4 GPU.

Execution result:

```text
GPU processed images: 100
