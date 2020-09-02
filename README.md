# Computer-Vision
my Computer Vision projects

## Plant Classification
Purpose of the competition: To classify plants into 4 classes.

![classes](/images/hist_of_classes.png)

The training images looked like

![batch](/images/batch_of_plants.png)

For training, the ResNet50 neural network was used. The code was written on the Keras framework

![batch](/images/training.png)

## Semantic Segmentation Cloud
In this competition, I identified areas containing certain cloud formations on satellite images, with the names of the labels: Fish, Flower, Gravel, Sugar.

![classes](/semantic_segmentation_image/train_data.png)

For this task, I chose the U-net neural network.

![U-net](/semantic_segmentation_image/U-net.png)

Training loss and metric

![loss_and_metric](/semantic_segmentation_image/loss_and_metric.png)

Results on training data

![train_results](/semantic_segmentation_image/train_predict.png)

Results on validation data

![val_results](/semantic_segmentation_image/val_predict.png)
