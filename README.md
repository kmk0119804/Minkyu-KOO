# Domain-Adaptive Instance Segmentation for Far-Field Object Monitoring Using SAM-Based Weak Supervision and Noisy Student Self-Training 

## **Abstract:** 
Automating construction site monitoring through deep learning-based segmentation presents challenges due to the high cost of pixel-wise annotations. This study proposes a novel weak and self-supervised learning framework to enhance segmentation accuracy while reducing annotation burdens. Utilizing human-annotated bounding-box GT as prompts to the Segment Anything Model (SAM), we generate high-quality polygon mask labels from bounding boxes, which are refined via self-training. Compared to fully supervised learning models, the proposed method integrates Transfer Learning, Pseudo-Label Refinement, and the Noisy Student technique, improving Mask mean Average Precision (Mask mAP) by 3–63% across seven target domains. It is expected to achieve a segmentation Mask mAP of 72.27%. Additionally, the proposed method outperformed existing weakly supervised techniques, such as BoxSnake and BoxTeacher, by 18% and 25.95%, respectively, and further exceeded the performance of the point-based method such as PointWSSIS by 48.78%.

------------------------------------------------------------------------------------------------------------------------------------------------------------

### **Data and Code Availability:** 
Due to contractual and security restrictions, the complete dataset cannot be publicly shared. A subset of the dataset that is cleared for external release, together with a prototype implementation of the code, will be provided in a dedicated GitHub repository upon acceptance of the paper. All publicly released materials will exclude sensitive and proprietary information and will comply with privacy and security regulations.

------------------------------------------------------------------------------------------------------------------------------------------------------------

### **Status:** 
This repository corresponds to the manuscript currently under review for the journal -Automation in Construction-. All code and data will be made publicly available after the paper is accepted for publication.

