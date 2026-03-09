# Rebuild-Yolov1-from-scratch
This repository contains a from-scratch implementation of the YOLOv1 (You Only Look Once) architecture. This is a self-learning project designed to dive deep into the mechanics of object detection, loss functions, and grid-based predictions.

📖 Context & References
This implementation was built for educational purposes. The architecture and much of the logic are guided by the insights found in the following resources:

Textbook: A Comprehensive Review of YOLO Architectures in Computer Vision: From YOLOv1 to YOLOv8 and YOLO-NAS by Juan Terven, Diana-Margarita Córdova-Esparza, and Julio-Alejandro Romero-González.

Video Tutorial: [Insert YouTube Link Here]

🚀 How to Run
The project is designed to run seamlessly in Google Colab. Follow these steps to get started:

Open the Notebook: Upload the .ipynb file to your Google Colab environment.

Enable GPU: For efficient training, ensure your runtime is set to GPU.

Go to: Runtime > Change runtime type > Hardware accelerator > GPU.

Update Paths: Before running the cells, locate the path variables in the code and update them to match your Google Drive or local storage structure.

<img width="1602" height="122" alt="image" src="https://github.com/user-attachments/assets/4b263570-7883-48d5-8dbe-30a764db756a" />
<img width="772" height="45" alt="image" src="https://github.com/user-attachments/assets/3a5dae03-b39e-4f3e-8c75-fece547c7348" />



📊 Dataset
For training, it is highly recommended to start with a relatively small version of the Pascal VOC dataset.

Dataset Link: https://www.kaggle.com/datasets/734b7bcb7ef13a045cbdd007a3c19874c2586ed0b02b4afc86126e89d00af8d2

Strategy: I recommend training on a small sample first to ensure the loss is decreasing and the model is learning correctly before committing to a full training run.

🔍 Testing AI Performance
To evaluate how well the model is detecting objects, you need to trigger the testing logic within the main() function.

Locate the testing section in the notebook.

Uncomment the specific piece of code shown below:

<img width="1081" height="299" alt="image" src="https://github.com/user-attachments/assets/1ef956a5-7bfd-4b1b-b389-9246be8ea27d" />

Rerun the cell and call main() to see the model's predictions and performance metrics.

Final Note: this was made by a freshman college student for learning purpose, without pre-train process the model performance is kina worse compared to the newer model.


