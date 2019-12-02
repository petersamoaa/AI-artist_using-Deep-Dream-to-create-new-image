# AI-artist_using-Deep-Dream-to-create-new-image
This Project is about using Deep dream algorithm in order to extract the features that by inception net, and apply it on image
Here the idea is to apply gradient acent instead of gardient descent. that's mean increase the loss to boost the patterns that found in the image
in the context of image the feature detectors can be on different stages, the early stage is extract simple (low level) fewtures like edges. As we go further in the network the feature detectors become more and more able to extract more complex features like face.
what we are going to do is to get those features and project it on image to give the image affect the acid drug. like when the child set and looking at the clouds in the sky, the kid starts to imagin shapes for the clouds or try to extract shape from the clouds 
the idea behind this theorm is finding the gredient of the loss with respect to the image, then instead id apply minus sign to that gredient (gredient dscent) we will add + sign to apply gredient ascent. then define the learning rate or step size to define how aggressivly the features are applied on the image 
The mathmatical model for this network is like the following: 𝒙|_𝒏𝒆𝒘= 𝒙|_𝒐𝒍𝒅+𝒅𝒚/𝒅𝒙∗𝒍𝒆𝒂𝒓𝒏𝒊𝒏𝒈 𝒓𝒂𝒕𝒆 (𝒔𝒕𝒆𝒑 𝒔𝒊𝒛𝒆), however the gredient is going to be like the following: 𝑮𝒓𝒂𝒅𝒊𝒆𝒏𝒕=  𝒅𝒚/𝒅𝒙=𝒅(𝒂𝒄𝒕𝒊𝒗𝒂𝒕𝒊𝒐𝒏𝒔/𝒍𝒐𝒔𝒔)/(𝒅(𝒊𝒏𝒑𝒖𝒕 𝒊𝒎𝒂𝒈𝒆)" " )
The idea of activation here is that there are many layers in the network that combine many other layers before. Those layers are responsible to pattens that could be found in the image.
The whole idea here is investing the activations in the Networks. Activation here does not means activation functions but rather batch_normalization.
 
