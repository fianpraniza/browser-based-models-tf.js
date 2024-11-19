# Breast Cancer Classifier with TensorFlow.js
This project builds a breast cancer classifier using TensorFlow.js. The classifier predicts whether a diagnosis is malignant or benign based on provided data.
## File Description
### main.html
The primary file for:
- Loading the training dataset (`train.csv`) and testing dataset (`test.csv`) from the `data` folder.
- Preprocessing the data into tensors suitable for training.
- Building and training a neural network using TensorFlow.js.
- Testing the model using the testing dataset.
- Saving the trained model for later use.
### data/
This project uses the Breast Cancer Wisconsin (Diagnostic) Dataset, which is a classification dataset to determine whether breast cancer cells are benign or malignant.
This folder contains the datasets:
- `wdbc-train.csv`: The dataset used for training the model.
- `wdbc-test.csv`: The dataset used for testing and evaluating the model.
## Project Structure
    .
    ├── main.html          
    ├── data/               
    │   ├── train.csv   
    │   └── test.csv       
    └── README.md
## Tools Used
- **[Brackets](http://brackets.io/):** The main text editor for writing and editing code.
- **[Simple Web Server](https://github.com/schisma/simple-web-server):** Used to run a local server so that the HTML file can load the CSV data from the `data` folder.
## Getting Started
1. Ensure you have installed **Brackets** and **Simple Web Server** on your computer.
2. Set up the project folder structure as shown above.
3. Open a terminal or command prompt and navigate to the project folder.
4. Start Simple Web Server with the command:
   ```bash
   simple-web-server .
5. Open your browser and access:
    ```bash
    http://localhost:8080/main.html
6. The training process will start, and the results can be viewed in the browser's console log.
## Dataset Source
This dataset is publicly available at UCI Machine Learning Repository:
Breast Cancer Wisconsin (Diagnostic) Dataset
## Dependencies
TensorFlow.js: Ensure your main.html file includes the TensorFlow.js library:
```html
<script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs@latest"></script>
