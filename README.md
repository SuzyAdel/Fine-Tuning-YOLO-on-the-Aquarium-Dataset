# Fine-Tuning-YOLO-on-the-Aquarium-Dataset

# 🧠 What Are We Trying to Do?
We are fine-tuning a YOLO object detection model on an Aquarium image dataset. This means we want the model to:


✅ Take in an image (input)

✅ Predict which objects (like fish, jellyfish, sharks, etc.) are in the image

✅ Output bounding boxes around those objects, along with their class labels

🔁 So What’s the Input and Output?

| 🔹 **Type**      | 🔸 **Description**                                              |
| ---------------- | --------------------------------------------------------------- |
| **Input**        | A `.jpg` image from your dataset (e.g., an aquarium scene)      |
| **Ground Truth** | A `.txt` label file with object coordinates for that image      |
| **Model Output** | Bounding boxes + class labels the model predicts from the image |
