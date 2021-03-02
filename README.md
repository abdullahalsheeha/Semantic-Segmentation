# Semantic-Segmentation

The goal of projrct is to use semantic segmentation to classify each pixel of the car in the image and remove studio background.

### Data Set Summary & Exploration

#### 1. basic summary of the data set..

* The size of training set is 4070 images
* The size of the validation set is 509 images
* The size of test set is 509 images

#### 2. visualization of the dataset.

![download (2)](https://user-images.githubusercontent.com/61292363/109576338-a39d1b00-7b04-11eb-90cd-8e26dcaf13cf.png)

### Design and Test a Model Architecture

#### 1. Preprocessing the data

I decided to normalized each pixles in the image to be in range between 0 and 1 and resize the image data to the shape (128, 128, 3).

#### 2. Final model architecture

My final model consisted of the following layers:

![model](https://user-images.githubusercontent.com/61292363/109576618-2aea8e80-7b05-11eb-8e73-d44b2467fccf.png)



#### 3. Train/validation loss curves

![download](https://user-images.githubusercontent.com/61292363/109576787-7bfa8280-7b05-11eb-8d45-143a60b56326.png)

## Results

![download (1)](https://user-images.githubusercontent.com/61292363/109577125-207cc480-7b06-11eb-95ef-fabc09266991.png)

