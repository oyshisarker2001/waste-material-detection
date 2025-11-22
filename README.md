# Waste material detection using deep learning technology used like yolov8,yolov7 tiny,ssd_mobilenet, efficientdetD0
[Paper Link](https://link.springer.com/chapter/10.1007/978-3-031-62217-5_7)
Dataset contains overall 212 images with a
total of 20,297 annotations with an average of 97.5 per image across 14 classes namely
board boxes, burnt paper, glass waste, plastic bottles, packets, plastic bags, non-plastic
bottles, paper cups, paper waste, plastic spoons, plastic bowls, plastic plates, and plastic
cups. We divide the dataset into train/validation/test as (93/5/2). The resolution of the input
data is 416x416.

![dataset orientation](https://github.com/oyshisarker2001/waste-material-detection/assets/57029168/5e6936da-46c2-47ef-a536-4171a0692d6d)

The augmentations applied were Flip (Horizontal, Vertical), 90°Clockwise, CounterClockwise, Upside-Down, Saturation(Between -32% and +32%), Brightness (Between -14% and +14%), and Exposure (Between -13% and +13%)
![test valid trai](https://github.com/oyshisarker2001/waste-material-detection/assets/57029168/402fcaf1-4df7-455e-a954-bc659d236d6e)


# Comparision of all 4 model's mAP(mean average precision)

![2023-06-07](https://github.com/oyshisarker2001/waste-material-detection/assets/57029168/bfc7f331-134f-4921-ba69-3d6261fb1a62)

# Predicted image of Ssd_mobilenet)v2_fpnlite

![predicted image](https://github.com/oyshisarker2001/waste-material-detection/assets/57029168/7bcf77e3-ce31-4aa9-a2e9-0450458f3936)

# Predicted image of EfficientdetD0

![predicted image](https://github.com/oyshisarker2001/waste-material-detection/assets/57029168/640f215e-cc7c-4692-a502-c50e8d40ffab)

# Predicted image of Yolov7 tiny

![DJI_0134_JPG rf 33f201367ee3d88494f90c70cf034afe](https://github.com/oyshisarker2001/waste-material-detection/assets/57029168/badb667d-9059-4dbe-a2ac-e045501ed98c)

# Predicted image of Yolov8 
![predicted image](https://github.com/oyshisarker2001/waste-material-detection/assets/57029168/dfce9633-f7ec-46e0-9bac-b28583535d88)

#  Confusion  matrix of Yolov7 tiny
![confusion_matrix](https://github.com/oyshisarker2001/waste-material-detection/assets/57029168/6af2b4c4-88b7-4119-9c9c-6612cb634e09)

#  Confusion  matrix of Yolov8
![confusion matrix](https://github.com/oyshisarker2001/waste-material-detection/assets/57029168/6e13da0c-685f-4c07-b210-16fbcdf14b97)














