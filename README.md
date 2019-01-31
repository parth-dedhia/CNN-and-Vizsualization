# CNN-and-Vizsualization
Lets remove the blackbox involved in deep learning


Programming , oh !!!
That's really old now

Here we will see how computers can learn just like humans by giving them the examples. 
* Programming was writing as set of rules for computer in programming language and get work done
* Finding the exact rule was always a tough job as we need to manually check and dry run for all the test cases
* To solve this problem lets just start another approach to teach the computer , the one which humans follow (often called as experience)
* Instead of manually finding out the rules for all set of examples , we make a machine make rules from the examples given to them

Yepiee !!!!! Problem solved !!!!!

# Neural Network

Lets see how neural network work 

* Neural Network have been developed just keeping our brain in mind. 
* Just like the brain each neuron takes a decision and based on that decision we decide our action. 
* We take the input from input neurons (in real life sensory organs) and depending on the type of input some of the other neurons are activated and some are not ( approaching the first hidden layer ). 
* Similarly we can have many such layers that will help us to make more superior decision , based on previous decision.One can think of it as if we were to take some decision in life, so just like we eliminate some basic things as being not relevant and then take the relevant features and work on them. Kepping this process going on and then finally coming to a conclusion. 
* This removal of irrelavant information is done by the weights associated between the layers. 
* So one can see just like the brain each neuron think about how things are working and how relevant the information is and weights decide to take them to other neurons. (more on neural networks [here](https://www.youtube.com/watch?v=aircAruvnKk))

# CONVOLUTION NEURAL NETWORK

I will not be explaining how convolution networks work. There are many blogs about them. Check them out.I will hereby be focusing on the visualization part of it.

Recently they have been a state of art in computer vision. These networks have given extra ordinary results in classifying hundred objects with an accuracy better then humans (Imagenet competition)
They are being implemented almost everywhere around you
- Right from Google's self driving car to Google Lens 
- Bidu's System ([check this out](https://www.youtube.com/watch?v=wr4rx0Spihs))
- Googles photos face detection

These are the one that are on top of my mind. There are many many other examples.

Many people have worked with CNN using [Keras](https://keras.io/) , [Tesnorflow](https://www.tensorflow.org/) , [pytorch](https://pytorch.org/) and many other tools. Here we will start with visualization of of CNN and how it works.
I have trained the model using MNIST dataset (Hello World for Deep learning programmers :P) and I have tried to provide output of various layers for understanding how this model is working. We will also see the filters that are applied to see how the filters affect the output
