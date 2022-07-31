# COVID-19-Image-Classification-with-FastAI
COVID-19 Image Classification with FastAI

Algorithm
- ResNet50

Dataset
- X-ray images
- 3 Classes — COVID, NORMAL, PNEUMONIA
- Train —680 images, Validation —85 images, Test —124 images
Datasource: https://www.kaggle.com/c/aiat-hackathon-1-2020/data

Data Augmentation
- do_flip=True
- flip_vert=False
- max_rotate=25
- max_lighting=0.5
- max_zoom=1.5

Learning Rate
- 1e-4 to 1e-3

Final Results

![Alt text](https://github.com/vladipooh/COVID-19-Image-Classification-with-FastAI/blob/main/confusion-matrix-covid19.png?raw=true "Confusion Matrix")

![Alt text](https://github.com/vladipooh/COVID-19-Image-Classification-with-FastAI/blob/main/toplose-covid19.png?raw=true "Top losses classification
")
