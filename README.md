This project **"OCR for Nigerian Licence plate"** uses YoloV11 for license plate detection and Fast Plate OCR for reading plate text.

## Dataset used
The dataset used is comprised of **4365** images of cars with the Nigerian license plate, divided into 70% train, 20% test and 10% validation. Due to the upload size restriction of github, the link to the dataset is provided [here](https://app.roboflow.com/abiodun-projects/license-plates-o3clj-uni85/4).

## Plate detection model
The *yolov11s.pt* model was used for detection of license plate due to its high accuracy and moderate computational cost. Click [here](https://docs.ultralytics.com/models/yolo11/#supported-tasks-and-modes) to check documentation

## OCR model
The model used is **fast-plate-ocr**, a lightweight and fast OCR framework for license plate text recognition. Click [here](https://ankandrew.github.io/fast-plate-ocr/latest/) for model documentation.

## Project Workflow
Data collection

      |      
Data Preprocessing and Augmentation

      |      
Detection model training

      |      
Cropping out detected plate

      |      
Plate OCR
