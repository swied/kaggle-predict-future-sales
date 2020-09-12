# Notebooks

## RapidsAI

If you wish to run the [Tutorial-RapidsAI.ipynb](Tutorial-RapidsAI.ipynb) notebook, then you will need to create a new environment.  The instructions for this are given below.

1. Create a new environment using the Anaconda Navigator UI:
   1. Enter `anaconda-navigator` in the termilal to open the UI application
   2. Click on the 'Environments' tab, and then click the button, "+ Create."
   3. Type "rapids" for the environment name, and then select "Python 3.6" from the menu.

2. Install Python packages from the terminal:
   1. `conda activate rapids`
   2. `conda install -c rapidsai -c nvidia -c conda-forge     -c defaults rapids=0.14 python=3.6`
   3. `conda install matplotlib`
   4. `conda install scikit-learn`
   5. `jupyter notebook tutorial-rapidai.ipynb` # This will open the notebook in Jupyter

	**Note:** See this page for more information regarding the [installation of RapidsAI](https://rapids.ai/start.html)

	There is a useful tutorial for RapidsAI on KDNuggets:  https://www.kdnuggets.com/2019/07/accelerate-data-science-on-gpu.html

## FastAI V1

If you wish to run the [Tutorial-FastAI.ipynb](Tutorial-FastAI.ipynb) notebook, then you will need to create a new environment. The instructions for this are given below:

1. Create a new environment using the Anaconda Navigator UI:
   1. Enter `anaconda-navigator` in the termilal to open the UI application
   2. Click on the 'Environments' tab, and then click the button, "+ Create."
   3. Type "fastaiv1" for the environment name, and then select "Python 3.6" from the menu.

2. Install Python packages from the terminal - per the instructions from 
   1. `conda activate fastaiv1`
   2. `conda install -c pytorch -c fastai fastai`
   3. `conda install h5py`
   4. `jupyter notebook Tutorial-FastAI.ipynb` # This will open the notebook in Jupyter

## Tensorflow & Keras (GPU)

If you wish to run the [Tutorial-Tensorflow.ipynb](Tutorial-Tensorflow.ipynb) notebook, then you will need to create a new environment. The instructions for this are given below:

1. Create a new environment using the Anaconda Navigator UI:
   1. Enter `anaconda-navigator` in the termilal to open the UI application
   2. Click on the 'Environments' tab, and then click the button, "+ Create."
   3. Type "tensorflow" for the environment name, and then select the latest version of Python from the menu.  

2. Install Python packages from the terminal - per the instructions from 
   1. `conda activate tensorflow`
   2. `conda install -c anaconda tensorflow-gpu`
   3. `conda install -c anaconda keras-gpu`
   4. `conda install -c anaconda pandas`
   5. `conda install -c anaconda matplotlib`
   6. `conda install -c anaconda seaborn`
   7. `conda install -c conda-forge xgboost`
   8. `conda install -c anaconda tqdm`
   9. 
   10. `jupyter notebook Tutorial-TensorFlow.ipynb` # This will open the notebook in Jupyter

   







