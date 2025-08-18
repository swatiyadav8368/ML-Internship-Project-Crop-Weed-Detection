### Project 5: Crop and Weed Detection

#### Project Overview

This project focuses on building a computer vision model to automatically detect and classify crops and weeds in agricultural images. The goal is to develop a system that can be used for precision agriculture, enabling automated spraying of pesticides only on weeds, thereby reducing chemical waste and improving crop health.

\<br\>

#### Methodology

The solution was developed using a deep learning approach with the following key technologies:

  * **Programming Language:** Python
  * **Environment:** Google Colab with GPU acceleration
  * **Model:** YOLOv8n (a fast and efficient object detection model)
  * **Dataset:** A custom dataset containing 1300 images of sesame crops and various weeds, with annotations in YOLO format.

The project workflow included:

  * **Data Preparation:** Correctly structuring the dataset and creating a `data.yaml` configuration file.
  * **Model Training:** Training a pre-trained YOLOv8n model for 50 epochs on the custom dataset.
  * **Model Evaluation:** Using `val()` to get quantitative metrics and generating plots like `results.png` and a confusion matrix.
  * **Inference:** Making predictions on unseen images to visually demonstrate the model's performance.

\<br\>

#### Key Results

After training for 50 epochs, the model achieved the following performance on the test set:

  * **mAP50:** 0.8884
  * **Precision:** 0.8208
  * **Recall:** 0.8463
    The model successfully detects and classifies crops and weeds, demonstrating strong performance for this task.

\<br\>

#### How to Run the Code

You can run the entire project by opening the provided Colab notebook.

1.  Click on the `Project_5_Crop_Weed_Detection_Colab_Workflow.ipynb` file in this repository.
2.  Click the "Open in Colab" button at the top of the page.
3.  Run the cells sequentially from top to bottom. The notebook will handle all data setup, model training, and evaluation automatically.

\<br\>

#### Dataset

The dataset used in this project can be accessed from the following link:

  * [Project 5 Dataset on Google Drive](https://drive.google.com/drive/folders/1gosoWLjTJjhyYZJ7qiZZ9I4jcoEPrfAK?usp=sharing)

\<br\>

#### Final Report

  * [Final Report PDF](https://github.com/swatiyadav8368/ML-Internship-Project-Crop-Weed-Detection/blob/main/Agriculture_Swati_USC_UCT.pdf)
- (https://drive.google.com/drive/folders/1gosoWLjTJjhyYZJ7qiZZ9I4jcoEPrfAK?usp=sharing)
