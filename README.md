# TensorFlow-object-detection-_-MiniProj

## TensorFlow Object detection API 
    
1. Here we have used the ssd_mobilenet_v2_fpnlite 320x320 for object detection
2. The pretrained models are cloned and imported from [tensorflow/models](https://github.com/tensorflow/models) 
3. We use the tensorflow_gpu - 2.9.1 along with CUDA 11.2 version and CUDNN 8.1.0 compatible with corresponding CUDA

### Procedure (Windows):- 
     
 * First we install all the dependencies regarding the project onto a virtual env "tensorflow" by    
   running this on cmd by (assuming anaconda is already installed on your machine)
   ```
   conda create -n tensorflow pip python=3.9
   ```
   ```
   conda activate tensorflow
   ```
 * Once you have activated your virtual environment, 
   the name of the environment should be displayed within brackets at the beggining of your cmd path specifier, e.g.:  
   ```
   (tensorflow) F:\Suppi\My_Project>
   ```
 * Install the Tensorflow pip package by 
   ```
   pip install --ignore-installed --upgrade tensorflow==2.9.0
   ```
 > Note: We need to install Protobuf and Protoc before proceeding with installing other dependencies 
 
### * All the Available Info are provided in here [TensorFlow 2 Object Detection API tutorial](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html)
      
 * After following through the above processes, just clone this repo and execute [Tutorial.ipynb](https://github.com/SinisterSup/TensorFlow-object-detection-_-MiniProj/blob/main/Tutorial.ipynb)
 
 * The required checkpoints are already trained and stored in [Tensorflow/workspace/models/my_ssd_mobnet/](https://github.com/SinisterSup/TensorFlow-object-detection-_-MiniProj/tree/main/Tensorflow/workspace/models/my_ssd_mobnet)
 
 
> ## If you want to build the CNN model yourself try executing [Proj.ipynb](https://github.com/SinisterSup/TensorFlow-object-detection-_-MiniProj/blob/main/Proj.ipynb) under the same conda environment (tensorflow) 
 
 
   # Thank You
   
   
