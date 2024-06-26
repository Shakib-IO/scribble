- Torch and Pylint [issue](https://www.cluzters.ai/forums/topic/659/py-torch-error-message-torch-has-no-member/view/post_id/2142?c=1597)
- [Previous Versions](https://pytorch.org/get-started/previous-versions/)
- [Pytorch Broadcasting work](https://stackoverflow.com/questions/51371070/how-does-pytorch-broadcasting-work) | [Video](https://youtu.be/QscEWm0QTRY)
- [Why do we need to call zero_grad() in PyTorch?](https://stackoverflow.com/questions/48001598/why-do-we-need-to-call-zero-grad-in-pytorch)
- [ipython notebook is not updating when I change my code](https://stackoverflow.com/questions/1907993/autoreload-of-modules-in-ipython)
- [Pytorch Quick Tip: Weight Initialization](https://youtu.be/xWQ-p_o0Uik)
- [Practical Deep Learning for Coders by Fast ai](https://course.fast.ai/)
- [PyTorch with an example](https://towardsdatascience.com/understanding-pytorch-with-an-example-a-step-by-step-tutorial-81fc5f8c4e8e)
- [Tensor](https://medium.com/data-science-365/real-world-examples-of-0d-1d-2d-3d-4d-and-5d-tensors-100b0837ced4)
- [CPU vs. GPU (Tensor Operations)](https://medium.com/@sahil_g/cpu-vs-gpu-pytorch-tensor-operations-50e215ff764a)
```
out.max(1) is a tuple containing two elements: the tensor of maximum values along dimension 1 and the tensor of indices corresponding to those maximum values.
out.max(1)[0] is used to obtain the tensor of maximum values along dimension 1 of the tensor out
out.max(1)[1] is used to obtain the tensor of indices corresponding to the maximum values along dimension 1 of the tensor
```
#### Pytorch Training
- [Connection between loss.backward() and optimizer.step()](https://stackoverflow.com/a/66192315)
- [Training Neural Networks](https://www.tomasbeuzen.com/deep-learning-with-pytorch/chapters/chapter4_neural-networks-pt2.html)


#### Library
- [TorchScale - A Library of Foundation Architectures](https://github.com/microsoft/torchscale)
- [Timm](https://timm.fast.ai/)
- [MyST Parser](https://myst-parser.readthedocs.io/en/v0.15.1/sphinx/intro.html)
- [Sphinx](https://www.sphinx-doc.org/en/master/usage/markdown.html)

#### Code
```
x = torch.randn(3,224,224) # x.dim() = 3
a = x.permute(0, 2, 1).view(x.size(0), x.size(2), 1, -1)  # Reshape and View
print(a.shape) # (3, 224, 1, 224)

y = torch.randn(1,3,256,256) # y.dim() = 4
b = y.permute(0, 2, 1, 3).view(y.size(0), y.size(2), -1, y.size(3))
print(b.shape) # torch.Size([1, 256, 3, 256])

```
