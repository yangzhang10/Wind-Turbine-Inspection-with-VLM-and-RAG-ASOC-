# Wind Turbine Inspection with VLM and RAG (ASOC 2025)

This repository contains the code and resources for our paper accepted in Applied Soft Computing (ASOC).
It implements a Retrieval-Augmented Generation (RAG) enhanced Vision-Language Model (VLM) framework for zero-shot wind turbine blade inspection.

## Requirements & Environment

Tested on Google Colab with T4 GPU
Key packages: torch, transformers, faiss, numpy, matplotlib

## Repository Structure

code/ Main implementation (training & inference)
test/ Testing images used in the paper
Reference/ Knowledge images for retrieval
README.md This file

## Usage

Open the notebook in Google Colab and select T4 GPU as the runtime.

## Datasets Used

This work uses open-source datasets:

[21] Foster, A., Best, O., Gianni, M., Khan, A., Collins, K., & Sharma, S. (2022). Drone footage wind turbine surface damage detection. In 2022 IEEE 14th Image, Video, and Multidimensional Signal Processing Workshop (IVMSP), pp.1–5. IEEE.

[57] Chen, X. (2023). Drone-based optical and thermal videos of rotor blades taken in normal wind turbine operation. IEEE Dataport. doi: https://dx.doi.org/10.21227/yzs5-1067

[60] Wang, W., Xue, Y., He, C., & Zhao, Y. (2022). Review of the typical damage and damage-detection methods of large wind turbine blades. Energies, 15(15), 5672.

Note: The datasets are not hosted in this repository. Please access them from the original sources above.

## Citation

If you find this repository useful, please cite our paper:

[Paper citation here, once available]

## License
MIT License
