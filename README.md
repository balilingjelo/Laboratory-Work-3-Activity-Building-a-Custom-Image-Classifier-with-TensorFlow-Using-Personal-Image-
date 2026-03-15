# Laboratory-Work-3-Activity_ImageDataset


# Google_Colab  https://colab.research.google.com/drive/1JkNyHGfgfQsO6wJtvZOdfrh5-qkkLFjB?usp=drive_link


# "Student Reflection & Explanation"
# 1. Dataset Preparation
○ How did you organize your dataset in Google Drive?

The image dataset was structured within Google Drive with a main folder labeled “ImageDataset.” Under the main folder, subfolders were created to correspond to each class label of the plant species category. The name of the subfolder acted as the label for the respective plant species.

○ Why is folder structure important for TensorFlow image loading?

It is important because it helps TensorFlow automatically identify and label images based on folder names. Each folder represents one class, making the dataset organized and easier to process during training. It also prevents loading errors and ensures the model learns correctly from each category

# 2. Model Training
○ What is the role of convolutional layers in image classification?

Convolutional layers are a key part of image classification in TensorFlow because they detect important visual features from images automatically. 
It's extract important features from an image so the model can identify what the image contains.

○ Why do we split data into training and validation sets?

So that the model can learn from a part of the data and then be tested on another part. This measures how accurate the model is and ensures that it works well on new images, not just on images used while training.

# 3. Performance Analysis
○ What accuracy did your model achieve?

The model reached about 100% training accuracy and 80% validation accuracy. This means it learned the training images very well, but its performance on new data is lower, which suggests slight overfitting.

○ How did the number of images affect the model’s performance?

The performance of the model depends on the images. The use of a large number of images is important to make the model perform better. The use of a large number of images enables the model to perform better by increasing the accuracy of the model. The use of a small number of images limits the performance of the model, thus reducing the accuracy of the model. More images make the model perform better.

# 4. Critical Thinking
○ What challenges did you encounter while using your own dataset?

When working with my own data set, several problems have arisen, such as the low number of images, the quality of the data, and the scarcity of variety in the data set. In addition, the data may have been unbalanced, which may have caused the accuracy to decrease, leading to poor performance of the model. It has taken a lot of effort to prepare the data set.

○ How can data augmentation improve your model?

Data augmentation is also helpful to the model as it increases the size and variety of the data. Data augmentation is a process whereby the model is given more varied data to work with by creating different versions of already existing images. This increases the variety of the data and reduces overfitting and increases the accuracy of the model.

