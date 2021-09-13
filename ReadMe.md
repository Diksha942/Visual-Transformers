# Visual Transformer (GitHub)

> link to the paper : https://arxiv.org/pdf/2006.03677.pdf

Convolutions treat all image pixels equally regardless of importance; explicitly model all concepts across all images, regardless of content; and struggle to relate spatially-distant concepts. Visual Transformers challenge this paradigm by 
1. representing images as semantic visual tokens and 
2. running transformers to densely model token relationships. 

We present an implementation of Visual Transformers in relation to the paper above. It has been deployed on a classification model trained on CIRAF10 dataset. 

The table below summarizes the loss and the number of parameters in each layer
![](https://i.imgur.com/t6CFIoe.png)


