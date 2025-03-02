
# Automatic Number Plate Recognition (ANPR) using YOLO & EasyOCR 🚗📷

This project implements Automatic Number Plate Recognition (ANPR) using YOLO for license plate detection and EasyOCR for text recognition. The model is trained on the Car Plate Detection dataset and can identify license plates from images and videos.
## Technologies Used
Pandas & XML Parsing for dataset handling

OpenCV for image processing

YOLOv8 (Ultralytics) for license plate detection

EasyOCR for character recognition

Matplotlib for visualization
## Dataset
The dataset is downloaded from Kaggle (andrewmvd/car-plate-detection) and contains:

Annotations in XML format (bounding boxes for license plates)
Images of vehicles with license plates


## Project Structure after running all cells
📂 Automatic-Number-plate-Recognition  
│── 📂 yolo_dataset  
│   ├── 📂 images/train  
│   ├── 📂 images/val  
│   ├── 📂 labels/train  
│   ├── 📂 labels/val  
│── 📂 runs/detect/train  
│── 📜 license_plate.yaml  
│── 📜 anpr_detection.ipynb  
│── 📜 README.md

## Flow
![image](https://github.com/user-attachments/assets/20620e16-f623-4910-a320-aa5ba3460f84)

## Screenshots

 ### Val batch:
![val_batch1_pred](https://github.com/user-attachments/assets/1d11a75c-b378-419e-b875-92c8b9398853)

### Inference:
![image](https://github.com/user-attachments/assets/add42dc6-7bac-4486-96ec-309c08478b3c)

## Epochs vs loss
![image](https://github.com/user-attachments/assets/e3ee7da0-6fcf-40f1-8aa1-1790fb27ded6)

    
## Results & accuracy
The YOLO model successfully detects license plates with high accuracy

EasyOCR extracts text from plates, achieving decent recognition accuracy

Loss curves and training progress are visualized using Matplotlib
