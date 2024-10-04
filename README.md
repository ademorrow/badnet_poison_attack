Deep Learning techniques in machine learning are evolving at a rapid rate. As their
capabilities expand and exponentially increase, so does the computational resources required to
train the models. As a results of resource limitations, a machine learning engineer might seek to
outsource model training to a cloud based third party entity. Outsourcing this step risks exposing
their model to malicious hackers seeking to plant a backdoor trigger into a trained model. In this
paper, I replicated an example of this form of attack on a Convolutional Neural Network trained
to recognize traffic signs. If successfully poisoned, the model could return a “speedlimit”
classification for a stop sign. In the real world, this attack scenario could force a self-driving
vehicle to run a stop sign and cause an accident. The predictive effects of different poison tag
colors and the degradation impact of the number of poisoned images used in the attack were
assessed.
