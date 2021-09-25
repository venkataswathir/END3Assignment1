# END3Assignment1
This contains the work done during the course on NLP
1. What is a neural network neuron?
A biological neuron is a basic buildng bolck of our nervous system. It helps in transmission of information to the brain. Neural network in the brain is a composition of millions of neurns which work to interpert the information coming in. A Neuron is a neural network is a temporary storage of information which with the help of some activation function, gives its final output. The basic idea is to sum up all the inputs with some weightage attached and apply an activation function and forward it to the next neuron.![IMG_20210925_061949](https://user-images.githubusercontent.com/76475606/134752556-1e1d5c3d-5c9a-44f4-9073-5e84f3343266.jpg)

2. What is the use of the learning rate?
Learning rate helps us get down to the optimum error a bit quickly with little hops. it is like getting down the stairs taking one step at a time or two steps at a time to reach the destination quickly.![IMG_20210925_063159](https://user-images.githubusercontent.com/76475606/134752661-e235e3d0-c99e-43d2-81a1-2f3170268144.jpg)

3. How are weights initialized?
weights can be initialized with a namalized random value. Initializing them with zero would be a dumb approach so we should go for a non-zero value. And most of the times we do it with a random method.
4. What is "loss" in a neural network?
the difference between the actual and the expected ressult is called loss. loss = mod(y - ypred)
5. What is the "chain rule" in gradient flow?
The change in the weight of perticular perceptron in going to be influenced by all the weights which helped the current perceptron calculates its own. So when we try to change the weight of a perceptron we also have to consider the whole weight travesal chain of the path.![1](https://user-images.githubusercontent.com/76475606/134752857-dfe993f7-1324-4432-92e3-3104a47b3972.png)

