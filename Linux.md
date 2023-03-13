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
- Get the CUDA list
```
ls -l /usr/local | grep cuda
````
- How to Check Your CPU in Linux
```
cat /proc/cpuinfo
OR
lscpu
```
```
ls -a	list all files including hidden file starting with '.'.
ls -d	list directories - with ' */'.
ls -l	list with long format - show permissions.
ls -F	Append indicator (one of */=>@|) to entries.
ls -lh	This command will show you the file sizes in human readable format.
ls -r	list in reverse order.
ls -i	list file's inode(index) number.
ls -ltr	View Reverse Output Order by Date.
ls -t	sort by time & date.
ls -n	It is used to print group ID and owner ID instead of their names.
ls -m	A list of entries separated by commas should fill the width.
ls -g	This allows you to exclude the owner and group information columns.
ls -q	Force printing of non-graphic characters in file names as the character `?';.
ls -Q	Place double quotations around the entry names.
```

#### Links
- [MultiCUDA: Multiple Versions of CUDA on One Machine](https://medium.com/@peterjussi/multicuda-multiple-versions-of-cuda-on-one-machine-4b6ccda6faae)
- [Install CUDA 11.2, cuDNN 8.1.0, PyTorch v1.8.0 (or v1.9.0), and python 3.9 on RTX3090 for deep learning
](https://medium.com/analytics-vidhya/install-cuda-11-2-cudnn-8-1-0-and-python-3-9-on-rtx3090-for-deep-learning-fcf96c95f7a1)
- [Installing Pytorch with CUDA support on Windows 10](https://pub.towardsai.net/installing-pytorch-with-cuda-support-on-windows-10-a38b1134535e)

#### Nvidia Install Steps
1. First install the Nvidia display driver from [Here](https://www.nvidia.com/download/index.aspx) (Fill the options with your GPU configuration).
2. To chck weather the the driver installed or not. Check ```nvidia-smi```.
3. Next check the CUDA version support [Pytorch](https://pytorch.org/get-started/locally/) or [Tensorflow](https://www.tensorflow.org/install/pip)
4. Now download the [CUDA Toolkit](https://developer.nvidia.com/cuda-toolkit-archive) that compatiable with pytorch or tensorflow.
5. Check the nvcc version ```nvcc --version```



##### CUDA Application Compatibility Support Matrix
![Screenshot from 2022-10-16 12-44-28](https://user-images.githubusercontent.com/65369990/196057463-68c0da93-ae3b-44aa-bb05-61a4d2f1cf01.png)

- [Different CUDA versions shown by nvcc and NVIDIA-smi](https://stackoverflow.com/questions/53422407/different-cuda-versions-shown-by-nvcc-and-nvidia-smi)
