# The Hundred Page Machine Learning

## Machine Learning

- Machine learning is a subfield of computer science that is concerned with building algorithms which,
    to be useful, rely on a collection of examples of some phenomenon. 
- These examples can come from nature, be handcrafted by humans or generated by another algorithm.

- It can also be defined as the process of solving a practical problem by:
    1. gathering a dataset
    2. alogrithmically building a statistical model based on that dataset.

## Types of Machine Learning

1. Supervised Learning
2. Unsupervised Learning
3. Semi-Supervised Learning
4. Reinforcement Learning

## Supervised Learning

- The dataset is the collection of labeled examples.
- $$\left\{ \left( \mathbf{x}_i, y_i \right) \right\}_{i=1}^{N}$$
- Each element x<sub>i</sub> among N is called a feature vector.
- A feature vector describes an example somehow. Example: gender, weight, etc and that value is called feature.
- The label y<sub>i</sub> can be either an element beloning to a finite set of classes, or a real number, or a more complex structure
    like a vector, a matrix, or a graph.
- It is a category to which an example belongs to.
- For example: In an spam detection, email messages can be classified into two classes {spam, not_spam}.
- The goal is to produce a model that takes feature vector x as input and provides output that allows to label for this feature vector.

## Unsupervised Learning

- The dataset is the collection of unlabeled examples.
- $\{x_i\}_{i=1}^{N}$, where x is a feature vector.
- The goal is to create a model that takes vector x as input and either transforms it into another vector or into a value that can be 
    used to solve a practical problem.
- For example: 
    - In <b>clustering</b>, the model returns id of the cluster for each feature vector in the dataset.
    - In <b>dimensionality reduction</b>, the output of the model is a feature vector that has fewer features than the input x.
    - In <b>outlier detection</b>, the output is a real number that indicates how x is different from a "typical" example in dataset.

## Semi-Supervised Learning

- The dataset contains both labeled and unlabeled examples.
- Quantity of unlabeled data is usually higher than labeled data.
- The goal to use the feature vectors to produce a label.
- Using many unlabeled examples hopes in making a better model. 

## Reinforcement Leaning

- It is a subfield of machine learning where the machine "lives" in an environment and is capable of perceiving the state of that environment as a vector of features.
- Machine can execute actions in every state and bring different rewards and could also move machine to another state in the environment.
- The goal is to lean a <b>policy</b>.
- A policy is a function f that takes the feature vector of a state as input and outputs an optimal action to execute in that state.
- Reinforcement learning solves a particular type of problem where decision making is sequential and the goal is long term like game playing, robotics, resource management or logistics.

## How Supervised Learning Works

- Supervised Learning process starts with gathering the data.
- Data are pairs of collection (inputs, outputs).
- Input could be anything like email messages, pictures or sensor measurements.
- Outputs are usually real numbers or labels like "spam", "not_spam", "cat", "dog", etc.
- In some cases, outputs are vectors like four coordinates of rectangle around a person in picture, sequences like ["adjective", "adjective","noun"] for input "big beautiful car".
- Classification learning algorithm that builds a model implicitly or explicitly creates a decision boundary.
- The decision boundary can be straight, or curved, or it can have a complex form, or it can be a superposition of some geometrical figures.
- The form of decision boundary determines the accuracy of the model.
- The form is calculated algorithimically or mathematically based on training data, differentiates one learning algorithm from another.
- Another differentiators: Speed of model building and prediction processing time. 