#### Commands

- How to determine Linux kernel architecture?
```
uname -a
# OR
uname -m && cat /etc/*release
# OR 
uname --help
````
- Search the available Drivers.
```
ubuntu-drivers devices
# OR
apt search nvidia-driver
```

#### Links
- [MultiCUDA: Multiple Versions of CUDA on One Machine](https://medium.com/@peterjussi/multicuda-multiple-versions-of-cuda-on-one-machine-4b6ccda6faae)
- [Install CUDA 11.2, cuDNN 8.1.0, PyTorch v1.8.0 (or v1.9.0), and python 3.9 on RTX3090 for deep learning
](https://medium.com/analytics-vidhya/install-cuda-11-2-cudnn-8-1-0-and-python-3-9-on-rtx3090-for-deep-learning-fcf96c95f7a1)
- [Installing Pytorch with CUDA support on Windows 10](https://pub.towardsai.net/installing-pytorch-with-cuda-support-on-windows-10-a38b1134535e)

##### CUDA Application Compatibility Support Matrix
![Screenshot from 2022-10-16 12-44-28](https://user-images.githubusercontent.com/65369990/196057463-68c0da93-ae3b-44aa-bb05-61a4d2f1cf01.png)
