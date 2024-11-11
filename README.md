# Calcium-concentration based learning algorithm in SNN
In spiking neural networks, the neurons communicate through one an-
other by using binary spikes. In addition to being more energy efficient
than traditional neural network architectures, this bio-inspired functioning
allows for the usage of more biologically plausible type of learning algorithms
such as with Spike-Time-Dependent plasticity in which the learning is based
around the spiking time difference between a pre- and post-connection neu-
ron. This unsupervised learning algorithm was inspired by learning mecha-
nisms in the brain and presents good results allowing to reach high accuracy
on some simple task even with basic models.

However, recent studies in neuroscience have proposed an alternative to
the STDP learning algorithm that appears to be more biologically plausible.
We propose here to adapt this learning algorithm and implement it in a basic
spiking neural network to observe its efficiency and compare the results its
results to the more traditional STDP protocols.