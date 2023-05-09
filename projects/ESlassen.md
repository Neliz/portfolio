<link rel="stylesheet" href="../styles.css">

## Image classification of insulated rail joints

**Project description:** ProRail wants to know the location of all its insulated rail joints. To ensure the safety of the railway system.

The goal was to developed a machine learning model and pipeline to accurately detect insulated rail joints in video footage.

### Solution
We created a machine learning pipeline that includes preprocessing, classification, postprocessing and linking to SAP. The pipeline uses a convolutional neural network (CNN) to extract frames from the video  and classify them as containing an insulated rail joint or not. We also used GradCAM to visualize the regions of the video frames that were important for the model's prediction. 

<img src="../images/gradcam.jpeg?raw=true"/>

The machine learning model achieved an accuracy of 99,5% on a test set of video footage, demonstrating its effectiveness in detecting insulated rail joints. The GradCAM visualizations provided insights into the model's decision-making process and helped identify areas for improvement.

### Results
The machine learning model and pipeline developed for ProRail provides an efficient and accurate solution for detecting electric rail welds in video footage, ensuring the safety and reliability of the railway system. The use of GradCAM further enhances the interpretability and transparency of the model's predictions.


### Used tools
PyTorch, ResNet50, GradCAM, OpenCV, Python, AzureML, QGIS, GeoPandas, Pandas, Docker, MLFlow, SQL, SQLalchemy, GIT, Azure DevOps, Numba, Blob Storage