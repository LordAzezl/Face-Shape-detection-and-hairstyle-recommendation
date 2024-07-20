## Face Shape Detection with Python 

This repository implements a Convolutional Neural Network (CNN) for face shape classification in Python. It can distinguish between five facial shapes: Heart, Oblong, Oval, Round, and Square.

###  Understanding the Process

The code is structured within a Jupyter Notebook, allowing for interactive exploration and clear explanations. Here's a breakdown of the steps involved:

1. **Data Preparation:**
   - Define paths to your training and testing image folders, organized by shape category.
   - Load images, convert them to grayscale (optional), and resize them for the CNN model.
   - You can optionally implement data augmentation techniques to increase training data diversity.
   - The notebook splits the data into training and testing sets for model evaluation.

2. **Defining the CNN Architecture:**
   - Design the CNN architecture using convolutional and pooling layers for feature extraction, followed by fully connected layers for classification. Experiment with different architectures and hyperparameters (number of layers, filter sizes) to potentially improve accuracy.

3. **Compiling and Training the Model:**
   - Specify the loss function (e.g., categorical cross-entropy) and optimizer (e.g., Adam) used for training.
   - Train the model by feeding it the training data in batches. During each iteration, the model makes predictions, calculates the loss, and updates its weights to improve accuracy.
   - The notebook allows you to monitor the training process by visualizing the loss and accuracy on both the training and validation sets (a subset used for hyperparameter tuning).

4. **Evaluation:**
   - After training, the model's performance is evaluated on the unseen testing data. The notebook compares the predicted face shapes with the actual labels to assess its effectiveness using metrics like accuracy.

5. **(Optional) Face Extraction:**
   - The notebook can be extended to incorporate face detection using libraries like MTCNN. This allows you to locate faces in new images and feed them to the trained model for shape classification.

###   Running the Script

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/LordAzezl/Face-Shape-detection-and-hairstyle-recommendation.git
   ```

2. **Install Libraries:**

   Ensure you have the required libraries installed using `pip install <library_name>`. Refer to the notebook for the specific list.

3. **Prepare Your Dataset:**

   Organize your face images into folders named after each shape category within the notebook's specified directories.

4. **Open the Jupyter Notebook:**

   Use a Jupyter Notebook environment to open the downloaded notebook file.

5. **Run and Explore:**

   Execute the code cells (either all at once or section by section) to train and evaluate the model. Feel free to modify the code and experiment with different settings to customize the face shape classification system!

###   Benefits of a Jupyter Notebook

* **Interactive Environment:** Experiment with parameters and visualize results within the same environment.
* **Documentation and Clarity:** Comments and markdown cells enhance code readability and understanding.
* **Visualization:** Libraries like Matplotlib allow you to visualize training progress and model performance.

This repository provides a well-structured and informative approach to face shape detection using CNNs. Dive into the code, explore different configurations, and build upon it to create your own unique face shape classifier!
