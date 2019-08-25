# Semantic-Segmenation-of-MRI-scan-using-Mask-RCNN
This project presents an implementation of semantic segmentation to detect brain tumor from MRI scan.

This is based on original Mask RCNN implementaion :
https://github.com/matterport/Mask_RCNN

1.)customImages contains train, val and test(predict) datasets.
2.)mrcnn folder contains pre-configurations for the mask rcnn model(Modify it according to your model).
3.)custom.py is the main file containing the implementation of model.

inspect_custom_data.ipynb: use this to visulaize mask.
inspect_custom_model.ipynb:use this to validate your model.
inspect_custom_weights.ipynb: use this to run and test your model.

I have used via tool(ver 1.6.0) to get the annotations in the format needed for the model.


References:
* Original Mask RCNN paper: https://arxiv.org/abs/1703.06870

* Refer below blogs to understand the working and changes to be made for custom segmentation:

https://engineering.matterport.com/splash-of-color-instance-segmentation-with-mask-r-cnn-and-tensorflow-7c761e238b46
  
https://www.analyticsvidhya.com/blog/2018/07/building-mask-r-cnn-model-detecting-damage-cars-python/
