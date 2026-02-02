# Wind Turbine Inspection with VLM and RAG (ASOC 2025)

This repository contains the code and resources associated with a paper submitted to *Applied Soft Computing (ASOC)*.  
The paper proposes a Retrieval-Augmented Generation (RAG)–enhanced Vision–Language Model (VLM) framework for zero-shot wind turbine blade inspection.

The manuscript was ultimately rejected after multiple rounds of review.

## Review History

- **Initial submission:** April 28, 2025  
- **First revision submitted:** September 8, 2025  
- **Second revision submitted:** September 20, 2025  

### Second Review Round
- The managing editor requested the inclusion of interactive plots.
- The editor-in-chief later confirmed that interactive plots were not required.

### Subsequent Handling
- After several months, the manuscript was sent out for an additional review round.
- More than 30 reviewers were invited.
- Many months later, I sent message to Elsvier to see what is going on with the manuscript since no editor handles it.

## Reviewer Decisions (2026-02-02)

- One reviewer, who participated in the first two review rounds, recommended acceptance with a high evaluation and stated that:
    All the comments of the referees (e.g. format, statistical validity, international perspective, DOI comparison) have been fully and professionally addressed.
    The article is of excellent scientific, methodological, innovative and writing quality and fully complies with the VSI.
    The 100% accuracy and interpretability make the article a valuable reference for industrial inspection, despite the small volume of data.
    Congratulations to the authors for the very high quality work and responsible response to the refereeing process. This article will make a significant contribution to the advancement of VLM applications in renewable energy.

- The reported accuracy and interpretability made the work a useful reference for industrial inspection, despite the limited data volume.

- Two additional reviewers recommended rejection.
  - One review emphasized the absence of publicly released source code at the time of review. (The author removed it because there are issues in the review process at that time.)


## Requirements & Environment

Tested on Google Colab with T4 GPU
Key packages: torch, transformers, faiss, numpy, matplotlib

## Repository Structure

1. code/ Main implementation (training & inference). Coming soon...
2. test/ Testing images used in the paper
3. Reference/ Knowledge images for retrieval
4. README.md This file

## Usage

1. Open the notebook in Google Colab and select T4 GPU as the runtime.

2. Upload the reference images to a cloud storage service (e.g., Aliyun, used in this paper.) and obtain the URL for each image. Save these URLs in a CSV file, and place the file in the designated path specified in the code.

3. Upload the test images to the cloud storage and obtain the URL for each image. Save these URLs in another CSV file, and place the file in the designated path specified in the code.

## Datasets Used

This work uses open-source datasets:

[21] Foster, A., Best, O., Gianni, M., Khan, A., Collins, K., & Sharma, S. (2022). Drone footage wind turbine surface damage detection. In 2022 IEEE 14th Image, Video, and Multidimensional Signal Processing Workshop (IVMSP), pp.1–5. IEEE.

[57] Chen, X. (2023). Drone-based optical and thermal videos of rotor blades taken in normal wind turbine operation. IEEE Dataport. doi: https://dx.doi.org/10.21227/yzs5-1067

[60] Wang, W., Xue, Y., He, C., & Zhao, Y. (2022). Review of the typical damage and damage-detection methods of large wind turbine blades. Energies, 15(15), 5672.

Note: The datasets are not hosted in this repository. Please access them from the original sources above.

## Citation

If you find this repository useful, please cite our paper:

[Here is citation]

## License
MIT License
