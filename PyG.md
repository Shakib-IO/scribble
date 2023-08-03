##### Step Env for [Torch==1.4.0](https://pytorch.org/get-started/previous-versions/#linux-and-windows-35) [Older [Verion]](https://data.pyg.org/whl/torch-1.4.0%2Bcu101.html)
```
# CUDA 10.1
pip install torch==1.4.0 torchvision==0.5.0
pip install torch_geometric==1.4.3
pip install torch-sparse==0.6.0 -f https://pytorch-geometric.com/whl/torch-1.4.0+cu101.html
pip install torch_scatter==2.0.3 -f https://pytorch-geometric.com/whl/torch-1.4.0+cu101.html
pip install torch_cluster==1.5.2 -f https://pytorch-geometric.com/whl/torch-1.4.0+cu101.html
```
[PyG](https://data.pyg.org/whl/torch-1.9.1%2Bcu102.html)
```
#CUDA 10.2 & Pytorch 1.9.1
pip install torch==1.9.1 torchvision==0.10.1 torchaudio==0.9.1
pip install torch_geometric==1.4.3
pip install torch_cluster==1.5.9 -f https://pytorch-geometric.com/whl/torch-1.9.1+cu102.html
pip install torch_scatter==2.0.9 -f https://pytorch-geometric.com/whl/torch-1.9.1+cu102.html
pip install torch-sparse==0.6.12 -f https://pytorch-geometric.com/whl/torch-1.9.1+cu102.html
pip install torch-spline-conv==1.2.1 -f https://pytorch-geometric.com/whl/torch-1.9.1+cu102.html

```

If installation is frozen 
```
pip install torch_scatter==2.0.9 --no-cache-dir -f https://data.pyg.org/whl/torch-1.10.0+cpu.html
pip install torch_sprase==0.6.12 --no-cache-dir -f https://data.pyg.org/whl/torch-1.10.0+cpu.html
```
