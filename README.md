
# Neural Style Transfer Project

## Project Overview

This project implements Neural Style Transfer (NST) using TensorFlow and the VGG19 model. The objective is to generate an image that combines the content of a target image with the style of a reference image. The VGG19 model is used for feature extraction, and the NST algorithm iteratively updates the generated image to minimize the content, style, and total variation losses.

![tajmahal_nst](https://github.com/Kamakhyamehta/Neural-Style-Transfer/assets/140178863/0045930d-fdc0-4ecb-8131-b68c85cbb3d0)

## Installation Instructions
### Step 1: Clone the Repository


    git clone https://github.com/Kamakhyamehta/Neural-Style-Transfer.git

    cd neural_style_transfer

### Step 2: Install Dependencies inside a Virtual Environment

Install the required libraries using the requirements.txt file.

    pip install -r requirements.txt

### Step 3: Download Pre-trained Weights

The VGG19 model weights are automatically downloaded by TensorFlow.


## Usage

### 1. Prepare Images

Ensure your content and style images are placed in the appropriate directories:

	•	Content images: data/content_images/
	•	Style images: data/style_images/

### 2.	Run the NST model:

After choosing new images, run all the code cells to avoid any error.

    •	Code: neural_style_transfer_ARies.ipynb/
The script will perform the style transfer for a specified number of iterations (default is 300) and save the intermediate results every 50 iterations.

### 3.	View results:
	Generated images: Result Images/ 
Check the above directory for the generated images. 
A new folder will be created and named in the 'datetime' format.
Each file inside the folder will be named according to the iteration number at which it was saved, e.g., generated_image_at_iteration_50.png.


## Examples:

![cheetah_nst](https://github.com/Kamakhyamehta/Neural-Style-Transfer/assets/140178863/33ba5278-5fbc-44b1-9a67-a3de0aad981f)
![peacock_nst](https://github.com/Kamakhyamehta/Neural-Style-Transfer/assets/140178863/25925e82-2ce9-40b5-b2bc-26a90cd4223f)






## Dependencies

List of all Libraries and Dependencies used in the project:
1. tensorflow
2. keras
3. numpy
4. tqdm
5. matplotlib
6. os
7. datetime

### Note
You can access all the information and details about this project from the report in 'Documentation' directory.
## Authors

- [Kamakhya Mehta](https://www.github.com/Kamakhyamehta), Pre-Final Year Student at IIT Roorkee. If you have any query or suggestions, do let me know at kamakhya_m@ch.iitr.ac.in

