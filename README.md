# Apple Tree Disease Prediction

 Link to the Kaggle dataset: [Click Here](https://www.kaggle.com/competitions/plant-pathology-2020-fgvc7/data)


## How to run the Notebook
Download the notebook and open it using Jupyter Notebook. Make sure to change the directory paths to the dataset on your machine. 


## Code sections
<details>

<summary>Loading data </summary>

The data is in the form of 

  - images in jpg that are labeled train or test and 
  - data labels in csv for train images

Load the data by downloading from Kaggle and copying the directory link. 

There are 4 classes-

1. combinations: one of the target labels
2. healthy: one of the target labels
3. rust: one of the target labels
4. scab: one of the target labels

</details>

<details>

<summary>Data preparation </summary>
This includes making separate folders for train and test images, and also sub folders for the 4 different classes/ target labels

Add new column Label to train.csv
<img width="514" alt="image" src="https://github.com/prachisinhaa/AppleTreeDiseasePrediction/assets/64536291/564facb2-f185-4f41-b5e4-4dc46648a2b2">

</details>

<details>

<summary>Image preprocessing </summary>
This was done using ImageDataGenerator()
</details>

<details>

<summary>CNN Model
</summary>

<img width="598" alt="image" src="https://github.com/prachisinhaa/AppleTreeDiseasePrediction/assets/64536291/7b25f6da-f79b-4376-9b12-09bc59592321">

</details>
