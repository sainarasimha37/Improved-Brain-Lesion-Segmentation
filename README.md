# Transfer Learning for Enhanced Brain Lesion Segmentation: A Study Utilizing U-Net and DeepLabV3 Models

## Overview
This research project focuses on the application of convolutional neural network models, specifically U-Net and DeepLabV3, for the segmentation of ischemic stroke lesions in MRI scans. Utilizing the multimodal datasets BRATS2015 and ISLES 2015, we demonstrate the efficacy of these models in medical image analysis.

## Datasets
- *ISLES 2015*: Comprises multimodal MRI scans of patients who have suffered ischemic strokes, including DWI, T1, T1c, T2, and FLAIR sequences.

The dataset is used to train and validate the models, providing a comprehensive view of the tumours and stroke lesions.

## Model Performance
- The *U-Net model* showed significant improvements in Dice Score and Sensitivity, indicating robust learning and generalization capabilities. It outperformed the DeepLabV3 model in both training and validation metrics.
- The *DeepLab model* demonstrated slower learning, suggesting a need for further optimization.

## File Formats
- .nii (Neuroimaging Informatics Technology Initiative): Used for storing MRI data.

## Research Findings
The U-Net model is more suitable for ischemic stroke lesion segmentation tasks with higher accuracy and sensitivity, making it a promising tool for medical diagnostics and research.

## Future Prospects
The research opens pathways for further optimization of U-Net and integration into clinical workflows. It also suggests potential for the model's application across different medical imaging modalities and conditions.

## Repository Contents
- /UNet: Contains the U-Net  model code and architecture.
- /DeepLabV3: Contains the DeepLabV3 model code and architecture.

## Accessing the Dataset and Models:
The dataset and the trained models are available for download from the following Google Drive location:
- [Dataset Folder](https://drive.google.com/drive/folders/1ZZpPimYgyFNFEotl3JxxejTh8bASThbu?usp=sharing)
- [Trained Models Folder of U-NET](https://drive.google.com/drive/folders/1soZX5wiIkcyEj2dpMduHY3BwmQVvcSe2?usp=sharing)
- [Trained Models Folder of DeepLabV3](https://drive.google.com/drive/folders/1oqcD02UHB6j083juN-BpstMJn8BaTAty?usp=sharing)


## Model Performance Tables

## Table 1: U-NET Model on Training Data

| Epoch | Dice Score | Sensitivity | Specificity |
|-------|------------|-------------|-------------|
| 1     | 0.3756     | 0.4719      | 0.9472      |
| 2     | 0.5957     | 0.5851      | 0.9911      |
| 3     | 0.6868     | 0.6562      | 0.9941      |
| 4     | 0.7157     | 0.6798      | 0.9949      |
| 5     | 0.7352     | 0.6950      | 0.9955      |

## Table 2: U-NET Model on Validation Data

| Epoch | Dice Score | Sensitivity | Specificity |
|-------|------------|-------------|-------------|
| 1     | 0.4837     | 0.4006      | 0.9948      |
| 2     | 0.5776     | 0.5796      | 0.9906      |
| 3     | 0.6127     | 0.5609      | 0.9943      |
| 4     | 0.6293     | 0.5647      | 0.9952      |
| 5     | 0.6368     | 0.5645      | 0.9956      |

## Table 3: U-NET Model Evaluation

| Metric      | Value  |
|-------------|--------|
| Dice Score  | 0.8823 |
| Dice Loss   | 0.1177 |
| Sensitivity | 0.8554 |
| Specificity | 0.9960 |
| Accuracy    | 0.9777 |

## Table 4: DeepLab Model Training Data Metrics

| Epoch | Dice Score Loss | Accuracy |
|-------|-----------------|----------|
| 1     | 0.3211          | 0.9222   |
| 2     | 0.3295          | 0.9608   |
| 3     | 0.3305          | 0.9644   |

## Table 5: DeepLab Model Validation Data Metrics

| Epoch | Dice Score Loss |
|-------|-----------------|
| 1     | 0.3225          |
| 2     | 0.3298          |
| 3     | 0.3305          |


## Usage
For working on the U-NET/DeepLabV3 Models to do the inference task, access the drive link to get access to the ISLES 2015 Data, and models. If you want to train the model again on your dataset ny using our U-Net Architectures and DeepLabV3 models, use the GPU’s to train the model and work on the inference.
