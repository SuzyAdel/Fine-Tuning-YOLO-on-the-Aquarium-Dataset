# Fine-Tuning-YOLO-on-the-Aquarium-Dataset
![image](https://github.com/user-attachments/assets/1a2ada33-0973-467d-84ef-34dba4f447d5)
![image](https://github.com/user-attachments/assets/b5ec379e-4e43-4fcb-9e8f-2384c9ee164d)

# 🧠 What Are We Trying to Do?
We are fine-tuning a YOLO object detection model on an Aquarium image dataset. This means we want the model to:


✅ Take in an image (input)

✅ Predict which objects (like fish, jellyfish, sharks, etc.) are in the image

✅ Output bounding boxes around those objects, along with their class labels
![image](https://github.com/user-attachments/assets/f43d6b6d-849d-4524-939a-d6686d8829df)

🔁 So What’s the Input and Output?

| 🔹 **Type**      | 🔸 **Description**                                              |
| ---------------- | --------------------------------------------------------------- |
| **Input**        | A `.jpg` image from your dataset (e.g., an aquarium scene)      |
| **Ground Truth** | A `.txt` label file with object coordinates for that image      |
| **Model Output** | Bounding boxes + class labels the model predicts from the image |

# Augmentation 
