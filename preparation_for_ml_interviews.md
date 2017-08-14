# Preparation for Interviews for ML Position

I will look for a full-time position in ML soon, so I list things that I think may be asked during the interviews.

Some knowledge come from the questions that were asked during my interviews and the questions that I heard were asked during others' interviews. Some are from what I read or what I learned.

The purpose of this list is for a quick review in case I overlook or forget something.

## Essential Knowledge

### ML
- Bias vs. variance
- No free lunch
- Probably approximately correct learning
- Occam's razor
- cross validation
- overfitting vs. underfitting
- unbalanced classes
- error bound: sample complexity, model complexity
- regularizer
- 0-1 loss, hinge loss, various loss functions ...
- derivative of sigmoid, softmax, relu, tanh
- information theory (information gain, mutual information)
- covariate shift
- kernel
- recursive partition
- bayesian inference
- KL divergence
- convex optimization (Lagrange multipliers)
- multi-armed bandits
- principle of maximum entropy
- bayesian optimization
- domain adaptation
- classifier in adversarial envonrinment

### Deep Learning
- gradient descent
- gradient vanishing and exploding
- hidden state of RNN (or LSTM)


## Tutorials and Links
### Deep Learning

[How to implement a recurrent neural networks, part 1](http://peterroelants.github.io/posts/rnn_implementation_part01/)
> Reference to how to implement backpropagation through time

[Mininal Neural Network case study](http://cs231n.github.io/neural-networks-case-study/)
> Content from Stanford CS 231, which contains the implementation of feed forward and back forward of neural networks in numpy. P.S. I was told that Google asked interviewee to manually implement gradient descent.

[Yes you should understand backprop](https://medium.com/@karpathy/yes-you-should-understand-backprop-e2f06eab496b)

[Backprop, intuitions](http://cs231n.github.io/optimization-2/)
> Content from Stanford CS 231


[Exploding and Vanishing Gradients](http://www.cs.toronto.edu/~rgrosse/courses/csc321_2017/readings/L15%20Exploding%20and%20Vanishing%20Gradients.pdf)

### ML

[SVM - dual problem](http://www.robots.ox.ac.uk/~az/lectures/ml/lect3.pdf)
> I read somewhere that dual problem was asked during interview for a ML position

[Kernel Methods and the Representer Theorem](http://web.eecs.umich.edu/~cscott/past_courses/eecs598w14/notes/13_kernel_methods.pdf)
> Representer theorem is the reason why optimization in SVM can be convert to the dual problem.

[Decision Tree Flavors: Gini Index and Information Gain](http://www.learnbymarketing.com/481/decision-tree-flavors-gini-info-gain/)

[Using Lagrange multipliers in optimization](http://kitchingroup.cheme.cmu.edu/blog/2013/02/03/Using-Lagrange-multipliers-in-optimization/)
> There is a simple way to calculate partial derivative in this post.

[Principle of Maximum Entropy: Simple Form](http://www-mtl.mit.edu/Courses/6.050/2003/notes/chapter9.pdf)
> A lecture note on principle of maximum entropy from an MIT course.

[Conditional Entropy (wiki)](https://en.wikipedia.org/wiki/Conditional_entropy)

[Mutual Information (wiki)](https://en.wikipedia.org/wiki/Mutual_information)

[Lecture note on Entropy and mutual information](http://www.info612.ece.mcgill.ca/lecture_02.pdf)

[Information gain](https://courses.cs.washington.edu/courses/cse455/10au/notes/InfoGain.pdf)
> Slides on information gain. It gives an intuitive explanation of entropy and information gain.

[Covariate Shift](http://sifaka.cs.uiuc.edu/jiang4/domain_adaptation/survey/node8.html)
> Good introduction to covariate shift and give an intuitive explanations on why covariate shift makes the performance suffer.

[Learning from unbalanced data] (https://www.svds.com/learning-imbalanced-classes/)
