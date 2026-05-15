This project detects laptops, phones, and monitors using a custom dataset.

Model: YOLOv8 trained on custom dataset

Classes: laptop, phone and monitor

Improved model changed from YOLOv8n to YOLOv8s and increased the number of epochs from 30 to 50

The imoroved model also includes  epochs=50,
    imgsz=640,
    degrees=15,
    fliplr=0.5, 
    hsv_v=0.4

Results: The model successfully detects objects with bounding boxes and confidence scores.
