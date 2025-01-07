# Cervix Whole-slide Image Grading via a Tumor Prior-Guiding Instance Clustering-incorporated End-to-end Multi-instance Learning Network 
Pan Huang, Student Member, IEEE, Mingrui Ma, Yi Zhang, Xin Luo, Fellow, IEEE

Our manuscript is in the peer review，and we will completely share the dataset and code after the peer review.

# Introduction
Accurate pathological grading is vital for the diagnosis, treatment, and prognosis of cervical squamous cell carcinoma, which is expected to focus on the tumor region. However, existing relational multi-instance learning (MIL) approaches overly learn nontumor instances, resulting in inaccurate CSCC pathology grading patterns. Inspired by this critical issue, this study proposes a tumor prior-guiding instance clustering-incorporated end-to-end multi-instance learning network, i.e., TicMIL, with three-fold ideas: first, we develop an end-to-end instance inhibition parallel learning algorithm that is able to build the precise feature representations for the CSCC pathology grading task; second, we incorporate the tumor priori-guiding instance clustering into the network for addressing the fuzzy labeling of cluster centers, as well as enhancing the model's representation ability to tumor instances; third, we model the imbalance between tumor and nontumor instances into the relational MIL, thus decreasing the decision entropy value of model for enlarging the learning margin to obtain high grading accraucy. Extensive experiments show that the proposed TicMIL comprehensively outperforms other SOTA MIL methods. It is able to represent the CSCC pathology grading patterns with high accuracy, proving its potential for clinical utility.  

---
![image](https://github.com/Baron-Huang/TicMIL/blob/main/Image/Main_Frame_for_TicMIL.png)


# Dataset
You could finds and applies the dataset by the link: https://drive.google.com/drive/folders/1bq8VS7r6Cn9dYqieGe-VzjQYu5dxW9B6?usp=drive_link.
