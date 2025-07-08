This project uses the camera to recognize historical landmarks and provides an historical audio narration about each site.

## Deep Learning Sections in the Report

This project includes several deep learning components that are documented in detail within the project report. Below are the relevant sections and their corresponding page numbers:

### Use Case and Sequence Diagrams  
Report Page: 22  
Describes the interaction between the user, the mobile device camera, and the deep learning model.

### Deep Learning Model Development and Integration  
Report Pages: 40–48  
Details the end-to-end development and integration of the deep learning model:

- Dataset and Data Preprocessing
  Covers how the dataset was collected, cleaned, resized, and normalized for model training.

- Model Comparison and Baselines  
  Compares different model candidates and evaluates baseline performances.

- Model Selection and Justification  
  Explains the rationale behind the chosen model architecture based on performance and efficiency.

- Model Architecture  
  Presents the detailed structure of the selected CNN model, including layer types and configurations.

- Training Details 
  Provides training parameters such as optimizer, loss function, learning rate, number of epochs, and batch size.

- Model Conversion and Integration 
  Describes the process of converting the PyTorch model to Core ML format and integrating it into the iOS app using Swift.

- Limitations of the Model
  Discusses challenges such as class imbalance, real-time performance, and domain adaptation issues.

### Tests and Results  
Report Pages: 65–68  
Summarizes the evaluation of the model including:

- Accuracy, precision, recall, and F1-score  
- Confusion matrix and interpretation  
