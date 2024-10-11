# Background

I try to maintain a blog but it requires a long time to write high quality interesting posts. So this space should work as a less formal dump for things I'm intereted in lately. I'll try to keep this as updated as possible.

# Last Update: [September 2024] 

# Learnability:

What can neural architectures (efficiently/practically/robustly/optimally) learn? What does using formal language learning (what is a good downstream task to see if a model has "learnt" a language? classification? prediction? something else?) as a sandbox tell us about inductive biases of modern neural nets?

1. \[1\] [Why are Sensitive Functions Hard for Transformers?](https://arxiv.org/pdf/2402.09963) _M. Hahn, M. Rofin_
2. \[2\] [The Expressive Capacity of State Space Models: A Formal Language Perspective](https://arxiv.org/pdf/2405.17394) _Sarrof et. al._ 
3. \[3\] [ON THE TURING COMPLETENESS OF MODERN NEURAL NETWORK ARCHITECTURES](https://arxiv.org/pdf/1901.03429) _Perez et. al._
4. \[4\] [InversionView: A General-Purpose Method for Reading Information from Neural Activations](https://arxiv.org/pdf/2405.17653) _Huang et. al._
5. \[5\] [What Algorithms can Transformers Learn? A Study in Length Generalization](https://arxiv.org/pdf/2310.16028) _Zhou et. al._
6. \[6\] [A Survey of Neural Networks and Formal Languages](https://arxiv.org/pdf/2006.01338) _Ackerman et. al._
7. \[7\] [What Formal Languages Can Transformers Express? A Survey](https://arxiv.org/pdf/2311.00208) _Strobl et. al._
8. \[8\] [NEURAL NETWORKS AND THE CHOMSKY HIERARCHY](https://arxiv.org/pdf/2207.02098) _Delétang et. al._
9. \[9\] [On the Ability and Limitations of Transformers to Recognize Formal Languages](https://aclanthology.org/2020.emnlp-main.576/) _Bhattamishra et.al_

# Boolean Functions, Automata, and Neural Approximations

Hahn in [1] explains why sensitive functions are difficult to approximate (learn) for transformers, but what is (formally) sensitivity of a boolean function? A neural net, with a intput and outputs in {0,1} with a step activation function is basically a boolean function, where each neuron acts as a boolean gate (binary inputs and outputs due to the step function), so can we retrieve the explicit boolean function it has learnt? Can we extend this to sequence modelling architecures (like transformers and RNNs) to extract an Ordered Binary Decision Diagrams (OBDDs) and how similar are these to finite automatas used to model regular languages? Is this useful?

1. 