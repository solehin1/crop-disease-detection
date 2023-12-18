# 🌱 Crop-Disease-Detection

Crop diseases are commonplace and arise from a multitude of factors, including fertilizer use, cultural practices, and environmental conditions. These diseases can significantly impact agricultural yields, consequently affecting the economy dependent on them.

Detecting crop diseases is crucial for farmers, and we have developed a Deep Learning-based crop Disease Detection system. Our approach employs Convolutional Neural Networks (CNNs) to classify leaf images into two distinct categories. The CNN code is implemented using the PyTorch framework. We utilize the Plant Village dataset for training our model, enhancing its ability to accurately identify and categorize crop diseases. 

## The DataSet
We employed the widely recognized PlantVillage Dataset, which is publicly accessible and renowned. Comprising approximately 54,305 images of crop leaves, the dataset was curated under controlled environmental conditions. The diverse collection encompasses images of 14 distinct crop species. To access the dataset, please follow [this link](https://data.mendeley.com/datasets/tywbtsjrjv/1)
> **Apple, Blueberry, Cherry, Corn, Grape, Orange, Peach, Bell Pepper, Potato, Raspberry, Soybean, Squash, Strawberry, and Tomato.**

Given the constraints of limited computational power, training a classification model locally on most standard machines becomes challenging. Consequently, we leverage the processing capabilities provided by Google Colab notebooks.


## Run Project in Google Colab

* Download the folder, which includes the pre-trained model file `plant_disease_model_1.pt` from [this location](https://drive.google.com/drive/folders/1qa2k-VcZ5_XHzlPhqH270QbutDIEMA_o?usp=sharing) and save it to your Google Drive.

* Run the `Single Image Plant Disease Detection.ipynb` notebook in Google Colab.

* Mount your Google Drive by following the instructions provided in the notebook.

* In interactive mode, select any test image for the system to analyze.

* The system will identify any diseases present in the image
* Accuracy based on test image dataset will be shown at the end of the section.

* Optionally, you can also utilize the `Training with Smaller Dataset.ipynb` notebook to train the model using a smaller dataset. This can be done in a Jupyter Notebook environment.

## Testing Images

* In the absence of leaf images, you can make use of the test images available in the `test-images` folder. 
* Each image is labeled with its corresponding disease name, facilitating the verification of the model's effectiveness.
