<link rel="stylesheet" href="../styles.css">

## Image classification of rail sleepers

**Project description:** ProRail wants to know the type of railway sleeper that is used on each section of the railway tracks to ensure the safety of the railway system. 

The goal was to developed a machine learning model and pipeline to accurately to accurately detect the type of railway sleeper in video footage. 
To accomplish this task, I had to find a way to segment the images of the railways and link these segments to Prorail's linear reference system. This required a deep understanding of geographic information systems and linear reference systems.

### Solution
I created a machine learning pipeline that includes preprocessing, classification, postprocessing and linking to SAP. The pipeline uses a convolutional neural network (CNN) classify each sleeper visible on each frame. 
I ensured that each frame of the railway images was categorized as part of a specific segment. Then, I used my knowledge of geographic information systems and linear reference systems to link these segments to Prorail's Spoortakken.

<img src="../images/dwarsliggers.png?raw=true"/>

### Results
The machine learning model and pipeline developed for ProRail provides an efficient and accurate solution for classifing sleeper type segments. 

### Used tools
PyTorch, ResNet50, OpenCV, Python, AzureML, QGIS, GeoPandas, Pandas, Docker, MLFlow, SQL, SQLalchemy, GIT, Azure DevOps, Numba, Blob Storage