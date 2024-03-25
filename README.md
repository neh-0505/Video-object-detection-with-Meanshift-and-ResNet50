ABOUT THIS PROJECT

by Implementing Meanshift algorithm (Machine Learning) with Resnet50 Tracking Algorithm (with Deep Learing using Pytorch), for a highway video full of cars, to detect an object (a white car which goes out of the frame in
sometime). And compare the IoU (Intersection over Union) value for object detection tasks to measure the accuracy of bounding box predictions. Video processing technique used: Meanshift Algorithm (Machine Learning), Resnet50 Tracking
Algorithm with Pytorch (Deep Learning), Also implemented Kernelized Correlation Filter tracking algorithm (KCF tracker). Performance metric used: IoU (Intersection over Union) value for object detection tasks to measure the accuracy of bounding box predictions.

MEANSHIFT TRACKING

Meanshift Tracking is a object tracking algorithm which works by iteratively shifting a window (or kernel) over the video data in such a way that it converges to the regions of maximum density or intensity. initially setup ROI calculating image histograms. and itirate the algorithm on ROI and track the objectMeanshift Tracking is a object tracking algorithm which works by iteratively shifting a window (or kernel) over the video data in  a way that it converges to the regions of maximsuchum density or intensity. initially setup ROI calculating image histograms. and itirate the algorithm on ROI and track the object
Performance: Meanshift tracking is a traditional computer vision-based algorithm that performs object tracking by iteratively shifting a window in the image space to maximize the similarity
between the target object and the candidate region. While meanshift tracking is effective in tracking objects with consistent appearance and motion, it may struggle with occlusions, abrupt changes in illumination, and complex backgrounds.
Speed: Meanshift tracking is generally faster than deep learning-based object detection algorithms like ResNet50. It operates in real-time or near-real-time on most modern hardware and is suitable for applications that require real-time tracking of objects in video streams.
Accuracy: The accuracy of meanshift tracking depends on factors such as the size and shape of the target object, the choice of feature representation, and the parameters of the meanshift
algorithm. While meanshift tracking can be accurate for certain types of objects and scenes, it may suffer from drift or loss of tracking if the target object undergoes significant changes in
appearance or motion.

OUTPUT:
masked video:

https://github.com/neh-0505/Video-object-detection-with-Meanshift-and-ResNet50/assets/140535795/35919baf-5bd9-4f6f-839a-4ac9a43c24c4

















Output of RESNET50 model detetcting white cars:

https://github.com/neh-0505/Video-object-detection-with-Meanshift-and-ResNet50/assets/140535795/1f5675ef-78da-425e-b94c-b8faa60c58c0


