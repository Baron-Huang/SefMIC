# Cervix Whole-slide Images Grading via Multi-instance Learning Network with Tumor Prior-guiding Instance Clustering
Mingrui Ma#, Pan Huang#, Student Member, IEEE, Wenjia Guo, Xiaoyi Lv*, Xin Luo*, Fellow, IEEE

Our manuscript is in the peer review，and we will completely share the dataset and code after the peer review.

# Introduction
Pathologic grading is important for the diagnosis, treatment, and prognosis of squamous carcinoma of the uterine cervix. Pathologists' grading decisions often focus on tumor region information, but existing relational multi-instance learning methods overly learn non-tumor instances, which will cause a decline in the model's ability to represent CSCC pathology grading patterns. Inspired by the above problem, we propose an end-to-end multi-instance learning network via tumor prior-guiding instance clustering (i.e., TicMIL) accompanied by these three-layered ideas: first, we implement an end-to-end instance-suppression parallel learning algorithm (EPCL), and then we implement an end-to-end instance-suppression parallel learning algorithm (EPCL). inhibition parallel learning algorithm (EIIPL) to address the problem of poor matching of feature representations learned from existing multi-instance learning to the CSCC pathology grading task; second, a tumor prior-guiding instance clustering (TIC) is proposed to address the problem of ambiguity in cluster core labels and to enhance the model's ability to represent tumor instances; and third, a relational multi-instance learning framework is introduced into the existing relationship multi-instance learning framework between tumor instances and non tumor with unequal effects in the existing relational multi-instance learning framework to reduce the decision entropy value of the relational multi-instance learning model. A large number of quantitative and qualitative experiments show that our TicMIL comprehensively outperforms other SOTA's multi-instance learning models in terms of mACC, AUC, F1, P, R, and other metrics. Second, in terms of feature representation, our TicMIL maintains the ability to represent Grade 2 and Grade 3 patterns well, and also enhances the ability to represent Grade 1. Overall, our model will be more valuable for clinical use.

---
![image](https://github.com/Baron-Huang/PacMIL/blob/main/Image/Main_Frame_for_PacMIL.png)


# Dataset
You could finds and applies the dataset by the link: https://drive.google.com/drive/folders/1bq8VS7r6Cn9dYqieGe-VzjQYu5dxW9B6?usp=drive_link.
