### Hello!
This is a documentation about the process of me learning deep learning using PyTorch.<BR>
To start off, I have built a linear regression using numpy from scratch in the above jupyter notebook. <BR>
This is to refresh my memory about chain rule, which is very important when it comes to understanding how the gradient of the loss function w.r.t the parameters are derived in PyTorch. 

![photo_2023-12-27_22-47-25](https://github.com/chingjie98/PyTorch/assets/35895182/a9641dd7-ec73-4f8a-b3ae-89ee51e47465){:height="18px" width="18px"}

Here are the general steps to a PyTorch deep learning process. 
1) Prepare your datasets -> usually numpy convert to tensor
2) Design model (input size, output size, forward pass) -> Make use of nn.module, creating ur layers using nn.Linear etc.
3) Training loop
- forward pass: compute prediction
- backward pass: gradients
- update weights

