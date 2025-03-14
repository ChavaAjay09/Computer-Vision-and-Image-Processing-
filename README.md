"# Computer-Vision-and-Image-Processing-" 
Dataset: UIEB (Underwater Image Enhancement Benchmark) 
 
The UIEB dataset is used for this project, as it provides a large collection of real
world underwater images captured in various environmental conditions. This 
dataset includes both raw and enhanced images, making it suitable for 
evaluating image processing techniques.


Combining Multiple Segmentation Methods for Better Accuracy 
Instead of relying on a single segmentation method, we implemented a hybrid 
approach: 
1. K-Means Clustering + Morphological Processing  
o Helps remove small noisy artifacts and enhance object boundaries. 
2. Mean Shift Clustering + Morphological Processing  
o Adaptive segmentation that does not require a fixed number of 
clusters. 
3. Graph-Based Segmentation (Felzenszwalb Algorithm)  
o Preserves fine details while segmenting objects based on similarity.
