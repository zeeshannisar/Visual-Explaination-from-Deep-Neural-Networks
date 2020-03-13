# Visual Explaination from Deep Neural Networks with CAM and Grad-CAM Techniques and Create Bounding-Boxes:
This Repository contains the implementation of visualization techniques for Deep Learning Neural Networks and also contains the implementation for creating Boundary-Boxes (Rectangle and Polygon) with these techniques. The visualization techniques are 
+ [Grad-CAM: Visual Explanations from Deep Networks via Gradient-based Localization](#grad-cam)
    + [Creation of BoundingBoxes (Rectangle and Poygon) using a Grad-CAM Heatmap](#bounding-boxes-with-grad-cam)
    
+ [CAM: Learning Deep Features for Discriminative Localization](#cam)

## Code Implementation and Results:

### Implementations:

#### Grad-CAM:

[Paper](https://arxiv.org/abs/1610.02391) 

[Code: Google Colab Notebook](https://github.com/zeeshannisar/Visual-Explaination-from-Deep-Neural-Networks/blob/master/Grad-CAM%20Approach/Grad-CAM-implementation.ipynb)

#### Bounding-Boxes with GRAD-CAM:
The following notebook creates BoundaryBoxes (Rectangle and Polygon) using Grad-CAM Heatmap output.

[Code: Google Colab Notebook](https://github.com/zeeshannisar/Visual-Explaination-from-Deep-Neural-Networks/blob/master/Creation%20of%20BoundingBoxes%20and%20Poygon%20using%20a%20Grad-CAM%20Heatmap/Implementation.ipynb)

#### CAM:

[Paper](https://arxiv.org/abs/1512.04150) 

[Code: Google Colab Notebook](https://github.com/zeeshannisar/Visual-Explaination-from-Deep-Neural-Networks/blob/master/Grad-CAM%20Approach/Grad-CAM-implementation.ipynb)



### **Results**:

#### Synthetic Data:

<p align="center">
    <img src="https://github.com/zeeshannisar/Visual-Explaination-from-Deep-Neural-Networks/blob/master/Read%20Me%20Images/synthetic.png">
</p>

#### Tuberculosis Data:

<p align="center">
    <img src="https://github.com/zeeshannisar/Visual-Explaination-from-Deep-Neural-Networks/blob/master/Read%20Me%20Images/TB.jpg">
</p>

#### BRATS-2017 Data:

<p align="center">
    <img src="https://github.com/zeeshannisar/Visual-Explaination-from-Deep-Neural-Networks/blob/master/Read%20Me%20Images/brats.png">
</p>

#### Bounding-Boxes with GRAD-CAM for Tuberculosis:
<p align="center">
    <img src="https://github.com/zeeshannisar/Visual-Explaination-from-Deep-Neural-Networks/blob/master/Read%20Me%20Images/BBox-Polygon-from-GRADCAM.png">
</p>

