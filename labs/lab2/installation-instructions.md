# IEOR4575 Assignments
Instructor: Shipra Agrawal\
Assistants: Yunhao Tang, Abhi Gupta

## Installing PyTorch or Tensorflow 2
```
You created a conda environment called ieor4575 for lab1. Now, you will install PyTorch or TensorFlow 2 to your ieor4575 environment. Please do not attempt to install both in the same conda environment, as this may result in additional complications. Choose PyTorch OR Tensorflow 2, whichever you prefer.
```

## Install PyTorch for the first time
```
1. $ conda activate ieor4575
(on a windows machine you might need to use 
$ activate ieor4575)

2. Go to https://pytorch.org/. Click Install.
3. Select the following options:
        PyTorch Build: Stable (1.7.1)
        Your OS: Choose from Linux, Mac, or Windows for your platform
        Package: Conda
        Language: Python
        CUDA: If you have a GPU, you may use it. However, it will not be necessary for class. Therfore, we encourage you to select None.
4. Enter the command found in "Run this Command" in the command line, assuming you have activated your ieor4575 conda environment already.
```

## Install TensorFlow 2 for the first time
```
1. $ conda activate ieor4575
(on a windows machine you might need to use 
$ activate ieor4575)

2. $ pip install tensorflow
```

## Open Lab
```
$ jupyter notebook <notebook name>
```