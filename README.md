 waste-material-detection
using deep learning technology used like yolov8,yolov7,ssd_mobilenet,efficientdetD0

dataset contains overall 212 images with a
total of 20,297 annotations with an average of 97.5 per image across 14 classes namely
board boxes, burnt paper, glass waste, plastic bottles, packets, plastic bags, non-plastic
bottles, paper cups, paper waste, plastic spoons, plastic bowls, plastic plates, and plastic
cups. We divide the dataset into train/validation/test as (93/5/2). The resolution of the input
data is 416x416.

![dataset orientation]
(https://github.com/oyshisarker2001/waste-material-detection/assets/57029168/5e6936da-46c2-47ef-a536-4171a0692d6d)

The augmentations applied were Flip (Horizontal, Vertical), 90°Clockwise, CounterClockwise, Upside-Down, Saturation(Between -32% and +32%), Brightness (Between -14% and +14%), and Exposure (Between -13% and +13%)
![test valid trai]
(https://github.com/oyshisarker2001/waste-material-detection/assets/57029168/402fcaf1-4df7-455e-a954-bc659d236d6e)

