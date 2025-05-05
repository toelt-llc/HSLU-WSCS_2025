# README

## Folder Structure
In this notebooks subfolder, you will find the two ML tutorial notebooks 
```
code/
│
├── 01 - ap1.ipynb                      # Classification model with Tensorflow
├── 02 - ap2.ipynb                      # Object Detection with YOLO
```

## Setup Instructions

### Run using Colab
All notebooks are designe to un primarily on colab, you will find a *run on colab* at the beggining of each notebook.  
**Runtime** : in colab you have the option to run on GPU, it is generally advised to select it for faster training and inference of models:  
 - Click *Connect* on the top right of the page
 - Select *GPU*

### Local Env
The notebook can be run on your local machine. Note : this is subject to more bugs and running times.  

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
