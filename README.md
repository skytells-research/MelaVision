# MelaVision
MelaVision is an AI-Powered algorithm designed to detect skin cancer.

### Overview
The purpose of this project is to create a tool that considering the image of a mole, can calculate the probability that a mole can be malign.

### Project Summary and motivation
The purpose of this project is to create a tool that considering the image of a
mole, can calculate the probability that a mole can be malign.

Skin cancer is a common disease that affect a big amount of
peoples. Some facts about skin cancer:

- Every year there are more new cases of skin cancer than the
combined incidence of cancers of the breast, prostate, lung and colon.
- An estimated 87,110 new cases of invasive melanoma will be diagnosed in the U.S.
in 2017.
- The estimated 5-year survival rate for patients whose melanoma is detected
early is about 98 percent in the U.S. The survival rate falls to 62 percent when
the disease reaches the lymph nodes, and 18 percent when the disease metastasizes
to distant organs.
- Early detection is critical!



#### Data:
To train this model the data to use is a set of images from the International
Skin Imaging Collaboration: Melanoma Project ISIC https://isic-archive.com.

The specific datasets to use are:

- ISIC_UDA-2_1:	Moles and melanomas. Biopsy-confirmed melanocytic lesions. Both malignant and benign lesions are included.
  - Benign: 23
  - Malign: 37


- ISIC_UDA-1_1	Moles and melanomas. Biopsy-confirmed melanocytic lesions. Both malignant and benign lesions are included.
  - Benign: 398
  - Malign: 159


- ISIC_MSK-2_1:	Benign and malignant skin lesions. Biopsy-confirmed melanocytic and non-melanocytic lesions.
  - Benign: 1167 (Not used)
  - Malign: 352


- ISIC_MSK-1_2:	Both malignant and benign melanocytic and non-melanocytic lesions. Almost all images confirmed by histopathology. Images not taken with modern digital cameras.
  - Benign: 339
  - Malign: 77


- ISIC_MSK-1_1: Moles and melanomas. Biopsy-confirmed melanocytic lesions, both malignant and benign.
  - Benign: 448
  - Malign: 224

As summary the total images to use are:

| Benign Images  | Malignant Images  |
| :------------- | :-----------------|
| 1208           | 849               |
