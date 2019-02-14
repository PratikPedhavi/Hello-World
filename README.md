# Digit-Recogniser
<h3>Neural Network Fully Connected</h1>
An easiest model inspired from the Tensorflow tutorial of Deep Learning Specialisation of Prof. Andrew Ng. 
The initial model had Layer 1 of 20 nodes, Layer 2 of 10 nodes followed by softmax layer of 5 nodes. 
After tweaking the number of layers to 64-24-10, the acuracy given was about 0.997 and accuracy on test data was about 0.95
Next chosen number of nodes in layers changes to 256-32-10, which gave train accuracy 0.99995 and on test data gives 0.973

This shows how important the network structure is for getting good accuracy.

<br><br><br>

<h1>CNN Network</h1>

Next emplyoed model is CNN with network structure as follows.<br>
CONV2D -> RELU -> MAXPOOL -> CONV2D -> RELU -> MAXPOOL -> FLATTEN -> FULLYCONNECTED <br>
<br>

This network gives an train accuracy of 0.995571, slightly lesser than 256-32-10 network, but performs better than it on Test data. A better defined and studied network can give more better results.

