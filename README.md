### Hello!
This is a documentation about the process of me learning deep learning using PyTorch.<BR>
To start off, I have built a linear regression using numpy from scratch in the above jupyter notebook. <BR>

This is to refresh my memory about chain rule, which is very important when it comes to understanding how the gradient of the loss function w.r.t the parameters are derived in PyTorch. 

<img src="https://github.com/chingjie98/PyTorch/assets/35895182/2fefe152-d9d0-4b16-ad0d-dfffd9d94b7f" width=50% height=50%><br><br>

Here are the general steps to a PyTorch deep learning process. <br>
1) Prepare your datasets -> usually numpy convert to tensor
2) Design model (input size, output size, forward pass) -> Make use of nn.module, creating ur layers using nn.Linear etc.
3) Training loop
- forward pass: compute prediction
- backward pass: gradients
- update weights

Learnt about how softmax layer and cross entropy loss works as well. 
Softmax essentially squeeze the output to be between 0 and 1, so that we are able to get the probabilities from the raw scores (logit).

<img src="https://github.com/chingjie98/PyTorch/assets/35895182/9fb689ce-e938-4a9e-97ec-b16c5b0c0eb2" width=50% height=50%><br><br>

Then, the cross entropy loss measures the difference between the predicted probabilities with the actual label. 
This works primarily with multiclass prediction problems. For binary, we need to use BCELoss which is Binary Cross Entropy Loss. 

<img src="https://github.com/chingjie98/PyTorch/assets/35895182/f0adbed0-cefd-4c65-be1a-1fd0ea80fe08" width=50% height=50%><br><br>

Several things to take note regarding the nn.CrossEntropLoss module however. 
<img src="https://github.com/chingjie98/PyTorch/assets/35895182/8480344c-b05f-4ec4-9820-e550338bec5f" width=50% height=50%><br><br>


