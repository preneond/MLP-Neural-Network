# MLP-Neural-Network
Implementation of MultiLayer Perceptron without libraries

### Overview
∂w optimization methods such as gradient descent in order to learn the network.
In backpropagation we divide the network into layers (modules). Each layer l is specified by the three following messages:
• forward message (zl+1 = f(zl)), describing the function realized by the layer, ∂zl+1
• backward message ( ∂zl ), Jacobian matrix giving sensitivities of all layer outputs w.r.t. to all of its inputs and
∂zl+1
• parameter message ( ∂wl ), giving sensitivities of all layer outputs w.r.t. to all layer
parameters.
