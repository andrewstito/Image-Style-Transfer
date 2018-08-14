# Image-Style-Transfer
Remember using applications like Prisma, Snapseed, Lucid etc.? Ever wondered how these things works?

We give a photo from our camera roll, then we select a design to combine both the images and we get a resultant new image which has the **_content_** of our input image and **_style_** of the design image. In the world of deep learning this is called **Style transfer**

The **_style_** of a painting is: the way the painter used brush strokes; how these strokes form objects; texture of objects; color palette used.
The **_content_** of the image is what objects are present in this image (person, face, dog, eyes, etc.) and their relationships in space.

### Pre-requisites
- [Pre-trained VGG19 network](http://www.vlfeat.org/matconvnet/models/beta16/imagenet-vgg-verydeep-19.mat) 
    _(VGG19 – a 19 weight layer network, is trained on a subset of the ImageNet database, which consists of more than a million images and can classify images into many object categories. (Developed and trained by Oxford's renowned Visual Geometry Group)_

- TensorFlow (v 1.9.0)
- Numpy & Scipy
- Pillow or PIL (Python Imaging Library) – library for image manipulation
