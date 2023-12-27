### Hello!
This is a documentation about the process of me learning deep learning using PyTorch.<BR>
To start off, I have built a linear regression using numpy from scratch in the above jupyter notebook. <BR>

This is to refresh my memory about chain rule, which is very important when it comes to understanding how the gradient of the loss function w.r.t the parameters are derived in PyTorch. 

<img src="https://github.com/chingjie98/PyTorch/assets/35895182/2fefe152-d9d0-4b16-ad0d-dfffd9d94b7f" width=50% height=50%>
<br>
Here are the general steps to a PyTorch deep learning process. 
1) Prepare your datasets -> usually numpy convert to tensor
2) Design model (input size, output size, forward pass) -> Make use of nn.module, creating ur layers using nn.Linear etc.
3) Training loop
- forward pass: compute prediction
- backward pass: gradients
- update weights

