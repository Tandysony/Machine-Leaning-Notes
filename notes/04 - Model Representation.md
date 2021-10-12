# Model Representation

To describe the supervised learning problem slightly more formally, our goal is, given a training set, to learn a function `h : X → Y` so that `h(x)` is a “**good**” predictor for the corresponding value of `y`. For historical reasons, this function `h` is called a hypothesis. Seen pictorially, the process is therefore like this:

![Model representation](./img/model_rep.png)

When the target variable that we’re trying to predict is continuous, such as in our housing example, we call the learning problem a regression problem. When y can take on only a small number of discrete values (such as if, given the living area, we wanted to predict if a dwelling is a house or an apartment, say), we call it a classification problem.