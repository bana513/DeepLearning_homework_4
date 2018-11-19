# Created by Bence Bial as a small homework for Deep Learning course (VITMAV45) at Budapest University of Technology and Economics
I used Open Images Dataset V4 - downloaded 400-100-100 tain-validation-test images in each categories,
where the images are distinct and the person is relatively large on them. I chose man and woman categories and made a binary classification problem. 
InceptionV3 model with imagenet weights was used. 
I achieved 78% accuracy on test set after learning 1 dense layer and a fixed imagenet network, then I also trained the upper layers of InceptionV3 model.