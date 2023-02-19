# CS231n notes and thoughts

I think CS231n is a REALLY good ML course. It teaches students the intuition behind neural networks and requires students get their hands dirty with implementation. A lot of online courses are too high level and only teaches students how to use ML frameworks, but those students would have a difficult time understanding what the algorithms are actually doing.

In this class, we go through the whole implementation of neural networks including gradient descent, forward passes, backward passes, and plugging all the pieces together. There are also sections on PyTorch, but I skipped most of it. I also skipped most of the inline questions.

The [notes](https://cs231n.github.io/) are REALLY good, but the main issue is that they do not cover much of assignment 3. In particular, I would have liked notes on GANs, SimCLR, and especially transformers, which I had a lot of difficulties with. I spent time going over slides, but they did not offer much context. I did not watch the online lectures, since the notes and other online materials turned out to be sufficient enough.

Overall, I would recommend this class to anyone who has some very high level understanding of ML after, lets say a intro or online course. It could also be good as a quick refresher. It took me about 22 days, 1 week per assignment on average, while I was somewhat busy with other things. For people getting into ML, I do believe its important to fully understand the neural network algorithms, rather than just using them in frameworks, and cs231n is a great class to accomplish that.

## Assignment 1
Assignment 1 includes KNN, SVM, softmax, and a basic nerual network. Its a good introduction, but the most challenging part was using numpy, wich I had not touched for 3 or so years. I had a lot of challenges translating for-loop code into vectorized numpy code in sections such as softmax loss and gradient. Numpy is not too hard to use, and after this assignment, the next two were much easier when it came to using the library

## Assignment 2
Assignment 2 introduces batchnorm, layernorm, dropout, convolutional, and pooling layers. I spent by far the most time on computing the batch normalization gradient, because apparently I did not understand the chain rule very well. Turns out if you know your stuff, most of the computations are basic calculas and algebra. The convolutional passes were not so hard to implement because we did not have to worry about vectorized code. An important caveat is that I skipped the pytorch and network visualization passes cause they don't seem that interesting.

## Assignment 3
Assignment 3 introduced RNN, LSTM, transformers, GANs, and SimCLR. All of these were interesting, and it made me realize that although there seeemingly infinite different neural network architectures out there, they are all based on the same underlying concepts and that someone with good foundations should be able to understand new architectures with easier effort than I thought.

These were all not too hard for me to understand except for transfomers, which required a lot of online reading to get an intution. I think the course should ease into transfomers by first introducing some sequence to sequence attention models that do not rely on self attention. I also had trouble with everything specific to NLP, such as implementing word vector representations and passes. [cs224n](https://web.stanford.edu/class/cs224n/) may be next on my list to learn NLP.
