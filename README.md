# Semi-fuzzy Multi-instance Clustering for Pathological Whole-slide Image Interpretable Recognition
Pan Huang, Member, IEEE, Mingrui Ma, Yi Zhang, Senior Member, IEEE, Xin Luo, Fellow, IEEE

Our manuscript is in the peer review，and we will completely share the dataset and code after the peer review.

# Introduction
Pathological whole-slide image interpretable recognition (PWSIIR) is vital for cancer diagnosis, treatment, and prognosis, which is expected to focus on the tumor region. However, existing relational multi-instance learning (MIL) approaches overly learn nontumor instances, resulting in inaccurate and non-interpretable recognition patterns represented from whole-slide images. Inspired by this critical issue, this study proposes an end-to-end semi-fuzzy multi-instance clustering for PWSIIR task, i.e., SefMIC, with three-fold ideas: first, we develop an end-to-end instance inhibition parallel learning algorithm that is able to build the precise feature representations for PWSIIR task; second, we incorporate the tumor priori-guiding instance clustering into the network for addressing the fuzzy labeling of cluster centers, as well as enhancing the model's representation ability to tumor instances; third, we model the imbalance between tumor and nontumor instances into the relational MIL, thus decreasing the decision entropy value of the model for enlarging the learning margin to obtain high grading accuracy. Extensive experiments were implemented on CAMELYON16, DHMC-Kidney, AMU-CSCC, and AMU-LSCC whole-slide image datasets, which show that the proposed SefMIC comprehensively outperforms other SOTA MIL methods. It is able to represent the PWSIIR task patterns with high accuracy, proving its potential for clinical utility.

---
![image](https://github.com/Baron-Huang/TicMIL/blob/main/Image/Main_Frame_for_TicMIL)


# Dataset
You could finds and applies the dataset by the link: https://drive.google.com/drive/folders/1bq8VS7r6Cn9dYqieGe-VzjQYu5dxW9B6?usp=drive_link.
