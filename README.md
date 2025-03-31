# README

## Folder Structure
In the code subfolder, you will find all the tutorial notebooks 
```
code/
│
├── 00 - Hold-out example with scikit-learn.ipynb               # Basic hold-out method example using scikit-learn
├── 01 - Introduction_to_keras_tuner.ipynb                      # Introductory guide to Keras Tuner
├── 02 - Easy_Network_with_Keras.ipynb                          # Simple neural network with Keras
├── 03 - hyperparameter_tuning_with_scikit_learn.ipynb          # Hyperparameter tuning using scikit-learn
├── 04 - Exercise_Supervised_Learning_2.ipynb                   # Supervised learning exercise
├── 05 - Converting_a_model_with_TF_Lite_converter.ipynb        # Converting models with TensorFlow Lite converter
├── 06 - Quantization_of_models_Complete_examples.ipynb         # Model quantization examples
├── 07 - Retrain_MobileNet_V2_classifier_for_the_Edge_TPU.ipynb # Retraining MobileNetV2 for Edge TPU
```

All notebooks demonstrate different machine learning techniques, covering fundamental concepts like model training, tuning, conversion, and deployment.

## Setup Instructions

### Run using Colab
All notebooks are designe to un primarily on colab, you will find a *run on colab* at the beggining of each notebook.  

### Local Env
The notebook can be run on your local machine. Note : this is subject to more bugs and changes.  

#### 1. Create a Conda Environment with Python 3.12

1. Open a terminal or command prompt.
2. Run the following command:
   ```bash
   conda create -n ml_notebooks python=3.12
   ```
3. Activate the environment:
   ```bash
   conda activate ml_notebooks
   ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

#### 2. Verify Installation

1. Ensure dependencies are installed:
   ```bash
   pip list
   ```
2. Test the notebooks in Jupyter:
   ```bash
   jupyter notebook
   ```

## Additional Notes
- Ensure TensorFlow and scikit-learn versions match your hardware setup.
- Additional dependencies may be required for Edge TPU support.
- If you face installation issues, update pip and conda before retrying.

