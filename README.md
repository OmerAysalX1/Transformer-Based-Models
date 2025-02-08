# Fashion Segmentation with Transformers

# 📝 Overview

This project focuses on image segmentation using Transformer-based models. The dataset used is iMaterialist (Fashion) 2020 in FGVC7, where real masks are extracted and evaluated using Interaction Over Union (IoU) scores. The final step involved testing the segmentation model and visualizing the results in images.

# 📂 Dataset

Name: iMaterialist (Fashion) 2020 on FGVC7

Content: Fashion images with annotated segmentation masks

Objective: Extract real masks and evaluate segmentation performance

# 🛠 Methodology

# 1️⃣ Extract Real Masks

✅ Processed the dataset to extract real masks

✅ Applied pre-processing: resizing, normalization, and shape transformation

# 2️⃣ Model Selection and Training

✅ Used a Transformer-based segmentation model from Hugging Face

✅ Trained the model on extracted masks for pixel-wise classification

# 3️⃣ IoU Calculation (Evaluation)

✅ Calculated Intersection over Union (IoU) scores for accuracy assessment

✅ Higher IoU values ​​indicate better segmentation performance

# 4️⃣ Testing and Visualization

✅ Tested the trained model on unseen images

✅ Comparing ground truth masks with predicted masks

✅ Visualized segmentation results with overlaid masks

# 5️⃣  Sample Result

![image](https://github.com/user-attachments/assets/5ea12ae7-fbf7-4075-9c57-b8b2f520def0)




# 📊 Results

✔ IOU values ​​were generated for each image

✔ Clothing regions were identified in test images

✔ Segmented mask boundaries were identified
