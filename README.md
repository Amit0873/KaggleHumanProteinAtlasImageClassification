Contest name: Human Protein Atlas Image Classification
Link : https://www.kaggle.com/c/human-protein-atlas-image-classification

Problem overview: Analyse the Protein cell from the biomedical image and find the pattern to accelerate the understanding of human cells behaviour and optimise disease [such as breast cancer, prostate cancer, colon cancer, diabetes, autoimmune diseases, ovarian cancer and renal failure].
About Data set: Each image is a 4-channel image. All image samples are represented by four filters (stored as individual files), the protein of interest (green) plus three cellular landmarks: nucleus (blue), microtubules (red), endoplasmic reticulum (yellow). The green filter is used to predict the label, and the other filters are used as references. There are in total 28 different labels present in the dataset. 
Data preprocessing : All the four channel has been overlayed and the image is transform to the shape of (192,192,4);
Batch size is 4
no of epoch = 2 (less number of epoch due to the large dataset & system GPU is not sufficient)
Details of CNN net has been printed on notebook. 
