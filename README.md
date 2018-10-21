# object_detection

# conda env setup
conda create -n tf_od python=3.6
source activate tf_od
pip install --upgrade pip
pip install tensorflow-gpu==1.11

# Tensorflow Object Detection API depends on the following libraries
pip install Cython
pip install contextlib2
pip install pillow
pip install lxml
pip install jupyter
pip install matplotlib

conda install -c hcc pycocotools