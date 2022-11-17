# OmniCity-v1.0

## Introduction
This project includes a part of the dataset and benchmarks of OmniCity-v1.0. The implemention is based on MMDetection. The complete dataset and benchmarks will be released soon.  

## Datasets
OmniCity Dataset including `Satellite-view` and `Street-view`, whitch are both divided into train and test set:
View|train/test|Image|Task-Annotation
----|----------|-----|----------
Satellite-view1|train|[Download](https://drive.google.com/file/d/1xl-WKuLJgHlb4jlwLfNv-IqdusZ_3GMB/view?usp=share_link)|[Instance](https://drive.google.com/file/d/1LYZBhJ-aKtkmpNAY6DGQKBJXY7ZSLjVd/view?usp=share_link)
Satellite-view1|test|[Download](https://drive.google.com/file/d/1kNskggj7ozHnqUoGWHrYUQYSwpuIzd5Q/view?usp=share_link)|[Instance](https://drive.google.com/file/d/1bPBSLma8J5CKHWSB1n-Jq_KYgmtZ7GX4/view?usp=share_link)
Satellite-view2|train|[Download](https://drive.google.com/file/d/1MUwZQMnxFbCxl1CTZHkQJDRr6RBavsmn/view?usp=share_link)|[Instance](https://drive.google.com/file/d/1bbhZ06aZlXEtk4XO0HBkhFKUKtwpyxdU/view?usp=share_link)
Satellite-view2|test|[Download](https://drive.google.com/file/d/16Oji7k-_v_hL8XQGTqzHzYYtPe053gpv/view?usp=share_link)|[Instance](https://drive.google.com/file/d/1De8HPutOa9LLtddJPPz378zrJAaBTW6M/view?usp=share_link)
Satellite-view3|train|[Download](https://drive.google.com/file/d/1meCjusZz0OlqvDN3-kBwzPi90oLXur36/view?usp=share_link)|[Instance](https://drive.google.com/file/d/1CJuJs83Ot6IUOSraE6FdmfyXqnR0JsA5/view?usp=share_link)
Satellite-view3|test|[Download](https://drive.google.com/file/d/10Qg79RQ4j2oaYJzN-DnsPb2WWVBWroAR/view?usp=share_link)|[Instance](https://drive.google.com/file/d/1PSOCJgpJU3F55uaglLwBBdcRsKNd97J2/view?usp=share_link)
Street-panorama|train|[Download](https://drive.google.com/file/d/1yiGiDs0U1z8eRyiTAh1lqXOThHjZ0-Jm/view?usp=share_link)|[Instance](https://drive.google.com/drive/folders/1uOIqfPvoARgOLbg4VuN2TlsDOYMJxS4P?usp=share_link)&[Landuse](https://drive.google.com/drive/folders/15MGK_zQkJPGlDl-riIL09VR6_Hdldxtx?usp=share_link)
Street-panorama|test|[Download](https://drive.google.com/file/d/1Yu_P-gDxtdSRWyKoWBmlQ4PBRhYftf4g/view?usp=share_link)|[Instance](https://drive.google.com/file/d/1KLT7CwjQ6pBGyXGfo0dAs1daSIVBMwUH/view?usp=share_link)&[Landuse](https://drive.google.com/file/d/1O8Btx11kpeENo1CLZlgeoWabQStijJEP/view?usp=share_link)
Street-Monoview|train|[Download](https://drive.google.com/file/d/1uvsQpw8LUVi1-O9RxHhO2vtGAMqBLloc/view?usp=share_link)|[Instance](https://drive.google.com/drive/folders/1qisutdGEjbmN-nEejs0TFg1XYXn-SWNJ?usp=share_link)&[Landuse](https://drive.google.com/drive/folders/1H53fw9v17gwfayxLfDUTOTy_AYIUXJg-?usp=share_link)&[Plane](https://drive.google.com/drive/folders/1Gm7rnTBOsZSVmXRV0W7TgliTxuoQG0I5?usp=share_link)
Street-Monoview|test|[Download](https://drive.google.com/file/d/1wNUZyK8wvghbIsiJHEvWVW7tUO1TjZ1d/view?usp=share_link)|[Instacne](https://drive.google.com/file/d/1v7PD6alZOwZ9_fFuchW0JEfoEn4cUcm3/view?usp=share_link)&[Landuse](https://drive.google.com/file/d/1J3PF1N5P1pryPRGddEj3j7wKbM9PzVYC/view?usp=share_link)&[Plane](https://drive.google.com/file/d/1eKmk5AIvoSQqlOMs-ReLwaiORF0izChV/view?usp=share_link)
## Overview of the models and its related tasks
Tasks: Instance segmentation, Land use segmentation, Plane segmentation.
### Satellite level: small view
Data Type |Size|Method | Task | Download
-------|-------|-------|---------|-----
Satallite image|512*512|Mask R-CNN|Instance segmentation|[Model](https://drive.google.com/file/d/17iHFTJUg-6dhzfCvA1rgGutrxGSRv0U-/view?usp=sharing)
Satallite image|512*512|MS R-CNN|Instance segmentation|[Model](https://drive.google.com/file/d/1a134TgMJuq2mFeI35Squ7j-z44zE7caT/view?usp=sharing)
Satallite image|512*512|CARAFE|Instance segmentation|[Model](https://drive.google.com/file/d/17m3dKxYIvguSJ6xDZ59ZawtFS_DkFLuA/view?usp=sharing)
Satallite image|512*512|Cascade|Instance segmentation|[Model](https://drive.google.com/file/d/1SnXI9GOonTGioDMC7KLn7Xi-qM4Ump7F/view?usp=sharing)
Satallite image|512*512|HTC|Instance segmentation|[Model](https://drive.google.com/file/d/1xocu_4D9vSS1UoCy_ko9hQWvOhnRWYMY/view?usp=sharing)
### Satellite level: medium view
Data Type |Size|Method | Task | Download
-------|-------|-------|---------|-----
Satallite image|512*512|Mask R-CNN|Instance segmentation|[Model](https://drive.google.com/file/d/17iHFTJUg-6dhzfCvA1rgGutrxGSRv0U-/view?usp=sharing)
### Satellite level: large view
Data Type |Size|Method | Task | Download
-------|-------|-------|---------|-----
Satellite image|512*512|Msak R-CNN|Instance segmentation|[Model](https://drive.google.com/file/d/1okuk0AsCZhFh-TZhAx9pNtr4B0NoJPOn/view?usp=sharing)
### Street level: Panorama
Data Type |Size|Method | Task | Download
-------|-------|-------|---------|-----
Panorama image|512*1024|Mask R-CNN|Instance segmentation|[Model](https://drive.google.com/file/d/1jvcyQTkl9h_U2i-_CRj6Q6UQ0j3UpCz4/view?usp=sharing)
Panorama image|512*1024|Mask R-CNN|Land use segmentation|[Model](https://drive.google.com/file/d/1v0-91uoksq3K3uZJ9FmLKIGEgw4roUj-/view?usp=sharing)
Panorama image|512*1024|MS R-CNN|Land use segmentation|[Model](https://drive.google.com/file/d/1z3a_4qvzh456iOFDhXN7Nz9N1tjhiKVl/view?usp=sharing)
Panorama image|512*1024|CARAFE|Land use segmentation|[Model](https://drive.google.com/file/d/18kURw1Zzfg88b3YxzzO3UH5baGg23usJ/view?usp=sharing)
Panorama image|512*1024|Cascade|Land use segmentation|[Model](https://drive.google.com/file/d/13hVlsRlRocEkXbL9Hbv5_ivP_dbzfQq7/view?usp=sharing)
Panorama image|512*1024|HTC|Land use segmentation|[Model](https://drive.google.com/file/d/17krXn77ixqJM9hZdviQhhDlnMtsfnB0b/view?usp=sharing)
### Street level: Mono-view
Data Type |Size|Method | Task | Download
-------|-------|-------|---------|-----
Mono-view image|512*512|Mask R-CNN|Instance segmentation|[Model](https://drive.google.com/file/d/1cV4FPuIAfHP4dRix8DucLt02FZebQflp/view?usp=sharing)
Mono-view image|512*512|Mask R-CNN|Land use segmentation|[Model](https://drive.google.com/file/d/1Ysly8Bzeb8ODfSfMsjo-x_zo9oAIAq7Y/view?usp=sharing)
Mono-view image|512*512|Mask R-CNN|Plane segmentation|[Model](https://drive.google.com/file/d/18MXiewv7UhHFyHGClQeuHrRs2zZZb2FV/view?usp=sharing)

## Usage
### Data preparation
If you want to use your own dataset test the models above, please prepare data following [MMdetection](https://github.com/open-mmlab/mmdetection)(Dataset in COCO format is preferred). And the data structure should look like below:
```
mmdetection
├── data
│   ├── coco
│   │   ├── annotations
│   │   ├── train2017
│   │   ├── val2017
│   │   ├── test2017
```
### Model test
With `OmniCity dataset`:
```
# single-gpu testing
python tools/test.py \
    ${CONFIG_FILE} \
    ${CHECKPOINT_FILE} \
    [--out ${RESULT_FILE}] \
    [--eval ${EVAL_METRICS}] \
    [--show]

# CPU: disable GPUs and run single-gpu testing script
export CUDA_VISIBLE_DEVICES=-1
python tools/test.py \
    ${CONFIG_FILE} \
    ${CHECKPOINT_FILE} \
    [--out ${RESULT_FILE}] \
    [--eval ${EVAL_METRICS}] \
    [--show]

# multi-gpu testing
bash tools/dist_test.sh \
    ${CONFIG_FILE} \
    ${CHECKPOINT_FILE} \
    ${GPU_NUM} \
    [--out ${RESULT_FILE}] \
    [--eval ${EVAL_METRICS}]
```
With `new dataset`:

* Prepare the dataset following the above rules
* Refer to the preceding operations

