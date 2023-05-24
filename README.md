# Deep-Neural-Netwrok-Image-recognition

This project provides a step-by-step implementation of a deep neural network for image recognition, specifically classifying pictures as either cat or non-cat. The implementation includes helper functions for initializing parameters, forward propagation, backward propagation, and parameter updates.

**Credits**

This project is based on the Deep Learning specialization course by Coursera and IBM.

**Instructions**

To build the neural network, follow the steps outlined below:

1- Initialize the parameters for a two-layer network and for an 𝐿-layer neural network.

2- Implement the forward propagation module, which involves:

    2-1 Completing the LINEAR part of a layer's forward propagation step, resulting in 𝑍[𝑙].
    
    2-2 Using an activation function (provided: relu/sigmoid) to compute the activation of each layer.
    
    2-3 Combining the previous two steps into a new [LINEAR->ACTIVATION] forward function.
    
    2-4 Stacking the [LINEAR->RELU] forward function L-1 times for layers 1 through L-1 and adding a [LINEAR-         >SIGMOID] at the end for the final layer 𝐿.
    
    2-5 This results in a new function called L_model_forward.
    
3- Compute the loss.
    
4- Implement the backward propagation module, which involves:

   4-1 Completing the LINEAR part of a layer's backward propagation step.
   
   4-2 Using the gradient of the activation function (provided: relu_backward/sigmoid_backward) to compute the          backward activation of each layer.
   
   4-3 Combining the previous two steps into a new [LINEAR->ACTIVATION] backward function.
   
   4-4 Stacking [LINEAR->RELU] backward L-1 times and adding [LINEAR->SIGMOID] backward in a new L_model_backward        function.
   
5- Update the parameters using gradient descent.

**Conclusion**

This project provides a comprehensive guide for implementing a deep neural network for image recognition. By following the step-by-step instructions and using the provided helper functions, you can build a two-layer neural network or an 𝐿-layer neural network and apply it to classify images as cat or non-cat.
