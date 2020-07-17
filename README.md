# artificial-neural-network
churning rate using artificial neural network

It is no secret that customer retention is a top priority for many companies;acquiring new customers can be several times more expensive than retaining existing ones. Furthermore, gaining an understanding of the reasons customers churn and estimating the risk associated with individual customers are both powerful components of designing a data-driven retention strategy. A churn model can be the tool that brings these elements together and provides insights and outputs that drive decision making across an organization.So it is used to predict as to which customers will be leaving the bank.

Churn rate (sometimes called attrition rate), in its broadest sense, is a measure of the number of individuals or items moving out of a collective group over a specific period. It is one of two primary factors that determine the steady-state level of customers a business will support.

Listing out the steps involved in training the ANN with Stochastic Gradient Descent:-
1)Randomly initialize the weights to small numbers close to 0(But not 0).
2)Input the 1st observation of your dataset in the Input Layer, each Feature in one Input Node.
3)Forward-Propagation from Left to Right, the neurons are activated in a way that the impact of each neuron’s activation.
   is limited by the weights.Propagate the activations until getting the predicted result y.
4)Compare the predicted result with the actual result. Measure the generated error.
5)Back-Propagation: From Right to Left, Error is back propagated.Update the weights according to how much they are
   responsible for the error.The Learning Rate tells us by how much such we update the weights.
6)Repeat Steps 1 to 5 and update the weights after each observation(Reinforcement Learning).
   Or: Repeat Steps 1 to 5 but update the weights only after a batch of observations(Batch Learning).
7)When the whole training set is passed through the ANN.That completes an Epoch. Redo more Epochs.
