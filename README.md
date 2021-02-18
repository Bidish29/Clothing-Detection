# Clothing-Detection
Using Instance Segmentation to Detect and Classify Garments.

Fashion is a vital part of our lives. Detecting and
classifying clothing items presents a significant challenge in
today’s world, where fashion is growing and changing at a rapid
pace. Through our paper, we aim to find how accurately we can
detect clothing items in images and make further predictions. We
implement two methods, bounding box and instance segmentation
for the analysis. We aim to find out how each of these detection
algorithms performs on images. Additionally, we use the output
of the bounding box and use it as the input to the segmentation
and see if there are any improvements in the detection. The
paper proposes to measure the prediction accuracy using the
Intersection Over Union and the Mean Average Precision metrics
and hence compare the results to observe which method is more
effective in classifying and predicting the clothing items. Further,
we determine the significant pixels which the model uses to detect
and classify the objects within an image. Our work indicates that
using the original images (40.4%) gives a slightly better score
than using the cropped images (34.3%) when measured using
the mean average precision metric; which is an indication that
the background affects the detection and classification of objects
in an image and cropping an image to omit the background does
not improve the accuracy.


The dataset used is the Deepfashion 2 dataset found at, https://github.com/switchablenorms/DeepFashion2
