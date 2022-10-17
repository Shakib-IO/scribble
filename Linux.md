#### Commands
- Details of Linux system
```
cat /etc/*release
```
- How to determine Linux kernel architecture?
```
uname -a
# OR
uname -m && cat /etc/*release
# OR 
uname --help
````
- Search/install available Drivers
```
ubuntu-drivers devices
# OR
apt search nvidia-driver
# OR 
sudo apt nvidia-driver-510 # CUDA 11.6
```

#### Links
- [MultiCUDA: Multiple Versions of CUDA on One Machine](https://medium.com/@peterjussi/multicuda-multiple-versions-of-cuda-on-one-machine-4b6ccda6faae)
- [Install CUDA 11.2, cuDNN 8.1.0, PyTorch v1.8.0 (or v1.9.0), and python 3.9 on RTX3090 for deep learning
](https://medium.com/analytics-vidhya/install-cuda-11-2-cudnn-8-1-0-and-python-3-9-on-rtx3090-for-deep-learning-fcf96c95f7a1)
- [Installing Pytorch with CUDA support on Windows 10](https://pub.towardsai.net/installing-pytorch-with-cuda-support-on-windows-10-a38b1134535e)

#### Steps
1. First install the Nvidia display driver from [Here](https://www.nvidia.com/download/index.aspx) (Fill the options with your GPU configuration).
2. To chck weather the the driver installed or not. Check ```nvidia-smi```.
3. Next check the CUDA version support [Pytorch](https://pytorch.org/get-started/locally/) or [Tensorflow](https://www.tensorflow.org/install/pip)
4. Now download the [CUDA Toolkit](https://developer.nvidia.com/cuda-toolkit-archive) that compatiable with pytorch or tensorflow.
5. Check the nvcc version ```nvcc --version```



##### CUDA Application Compatibility Support Matrix
![Screenshot from 2022-10-16 12-44-28](https://user-images.githubusercontent.com/65369990/196057463-68c0da93-ae3b-44aa-bb05-61a4d2f1cf01.png)
