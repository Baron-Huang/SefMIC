# Cervix Whole-slide Image Grading via Multi-instance Learning Network with Tumor Prior-guiding Instance Clustering
Pan Huang, Student Member, IEEE, Mingrui Ma, Xin Luo, Fellow, IEEE

Our manuscript is in the peer review，and we will completely share the dataset and code after the peer review.

# Introduction
Pathological grading is important for the diagnosis, treatment, and prognosis of cervical squamous cell carcinoma (CSCC). Pathologists often focus on the tumor region when making grading decisions. However, existing relational multi-instance learning (MIL) methods overly learn nontumor instances, which degrades the model's ability to represent CSCC pathology grading patterns. Inspired by the aforementioned issues, we propose an end-to-end multi-instance learning network via tumor prior-guiding instance clustering, i.e., TicMIL, with three-fold ideas. First, we develop an end-to-end instance inhibition parallel learning algorithm, which addresses the poor match between feature representations of existing MILs and the CSCC pathology grading task. Second, we propose tumor-priori guided instance clustering to solve the fuzzy labeling of cluster centers and enhance the model's representation ability toward tumor instances. Third, we introduce the relationship of unequal effects between tumor and nontumor instances into the relational MIL, which decreases the decision entropy value of the relational MIL model. Extensive experiments show that our TicMIL method comprehensively outperforms other SOTA methods for MIL. Next, our TicMIL method can represent the CSCC pathology grading patterns better than other SOTA methods of the MIL. Overall, our model is more valuable for clinical utility. 

---
![image](https://github.com/Baron-Huang/TicMIL/blob/main/Image/Main_Frame_for_TicMIL.png)


# Dataset
You could finds and applies the dataset by the link: https://drive.google.com/drive/folders/1bq8VS7r6Cn9dYqieGe-VzjQYu5dxW9B6?usp=drive_link.
