Stedin Data Science Analytics Community
=======================================

### Code, images and data used for the Data Science Analytics Community 'Deep Learning' session. 

#### TensorFlow installation (Windows)

When using tensorflow you have the choice to train your models on CPUs and GPUs. Installation differs slightly depending which version of TensorFlow you wish to use. 
The following installation steps are appropriate for a Windows machine with Python 3.5/3.6.
To check your version of python you can type `python` on your command prompt and you should receive something of the following form:

```
Python 3.5.2 |Anaconda custom (x86_64)| (default, Jul  2 2016, 17:52:12) 
[GCC 4.2.1 Compatible Apple LLVM 4.2 (clang-425.0.28)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> 
```

### Installation with pip

You must first ensure you are using an updated version of pip. To upgrade to the latest version of pip run:
```
pip install --upgrade pip
```
Once you have upgraded pip use the following commands to install tensorflow. To install the CPU verion run the following command:

```
pip install tensorflow
```

To install the GPU version of tensorflow run:

```
pip install --upgrade tensorflow-gpu
```
Note that the GPU version of tensorflow will not install if your machine does not have a GPU card with CUDA Compute Capability 3.0 or higher for building from source. The Stedin machines do not typically support this version so you will most likely have to use the CPU version unless you are using a virtual machine.

