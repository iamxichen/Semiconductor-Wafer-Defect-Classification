# Semiconductor-Wafer-Defect-Classification
Semiconductor wafer defect classification based on the WM-811K dataset

In this project, we will demonstrate how data science can be used in wafer fabrication to uncover defect patterns through analyzing wafer defect data.

A die, in semiconductors, is a block of the wafer on which a given functional circuit is fabricated. The wafer is cut (diced) into many pieces, each containing one copy of the circuit. Each piece is called a die. In the semiconductor manufacturing process, once the wafers are tested, a wafer bin map (WBM) is produced to provide information regarding the quality of a wafer and which dies have failed. 

Typically, experienced process engineers will analyze WBM to define wafer failure pattern types. However, this process is expensive and time-consuming. The goal of this project is therefore to develop a classification model for the automatic recognition of wafer map failure pattern types during semiconductor manufacturing processes to reduce manual work.

In this project, we developed a defect pattern classification method using a random forest classifier with an accuracy score of 0.815 using the WM-811K dataset from the MIR lab. A random forest classifier is an ensemble learning method for classification that operates by constructing a multitude of decision trees at training time. Among the different wafer defect types, the proposed method achieves the highest accuracy in detecting wafer maps with random, edge-ring, and donut defects. We conducted hyperparameter tuning to discover the best model. This is achieved with feature engineering, where the wafer map attributes are decomposed and aggregated to generate density-based, randon-based, and geometry-based attributes.

![image](https://user-images.githubusercontent.com/94267694/148795883-f77a01be-30fa-452e-b476-bd1723c53315.png)
