# Adaptive-Traffic-Control-Using-Deep-Learning-and-Arduino-Simulation
This repository contains the Author Accepted Manuscript (AAM) version of our conference paper. 

## Abstract
An efficient and intelligent traffic control system is essential for reducing unnecessary congestion and fuel wastage. This study presents a smart traffic control system that dynamically adjusts green light duration according to real-time traffic density. Three object detection models - YOLOv5, Faster R-CNN, and SSD - were implemented and evaluated on a traffic image dataset from Kaggle. YOLOv5 showed superior performance with the lowest inference times (72.59s for training, 3.21s for testing, and 6.80s for validation), outperforming Faster RCNN and SSD. Due to its speed, YOLOv5 was selected for further processing. The vehicle count detected by this approach was transmitted to an Arduino-based system simulated in SimulIDE, through serial communication. This approach focuses on reducing the wait time and enhancing traffic flow efficiency.

### Citation
Kumari, R., Suman, S., Dhanoa, J.K. (2026). Adaptive Traffic Control Using Deep Learning and Arduino Simulation. In: Saha, A.K., Sharma, H., Prasad, M., Gupta, P.K. (eds) Intelligent Vision and Computing. ICIVC 2025. Lecture Notes in Networks and Systems, vol 1712. Springer, Cham. https://doi.org/10.1007/978-3-032-10670-4_35

pp 429–440
