# PET
This is the official implementation of PET **(Personalized View Weighting with Data Enhancement Two-Pronged Contrast)** 
(Under Submission to CIKM 2024 Short Paper Track) 

---
### Supplementary Document
For additional data anlysis results and details about loss function, you can check here. [Supplementary Document.pdf](https://github.com/user-attachments/files/15701693/Supplementary.Document.pdf)

---

### Datasets
We use three widely used datasets for bundle recommendation, iFashion, NetEase and Youshu.
For the iFashion dataset, please unzip data.zip in the same folder.


--- 
### Run PET
1. **iFashion**
   ```bash
   python train.py -d iFashion -g [gpu_id]

2. **NetEase**
   ```bash
   python train.py -d NetEase -g [gpu_id]

3. **Youshu**
   ```bash
   python train.py -d Youshu -g [gpu_id]   
---
### Acknowledgement
This code is implemented based on the open source code from the paper **CrossCBR : Cross-view Contrastive Learning for Bundle Recommendation** (KDD '22).

