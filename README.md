# ComputerVision
Face alignment using facial landmarks in images

    Model 1
    
Sequential model using just two dense layers

![](./images/model1.png)

    Model 2
    
Sequential model three layers of convolution with activation and max pooling. Then three dense layer upon flattening.

![](./images/model2.png)

    Segmentation
 
Using features of the images to segment into a specified number of colours

    Segmentation of two colours
    
![](./images/twoSeg.png)
    
    Segmentation of five colours
 
 ![](./images/fivSeg.png)
 
    Graphical effects
    
 Using features to create a graphical effect of a mask which covers the nose and mouth and using the jaw line and ears as guides for overall shape of mask
 
  ![](./images/ge.png)
    
Credits

Using training images found: https://sussex.app.box.com/s/2nansy5fdps2dcycsqb7r06cddbbkskd
Using testing images found: https://sussex.app.box.com/s/1n1t93vx6em5vjzff6c6pr4685t7booh
