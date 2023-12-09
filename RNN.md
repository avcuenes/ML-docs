# RNN (Recurrent Neural Networks)

Architecture of a traditional RNNRecurrent neural networks, also known as RNNs, are a class of neural networks that allow previous outputs to be used as inputs while having hidden states. They are typically as follows:

![RNN](/pictures/RNN.png "RNN")
For each timestep t, the activation $a^t$ and the output $y^t$ are expressed as follows:

![eq](/pictures/equations.png "EQ1")


![eq](/pictures/eq2.png "EQ1")



|  Advantages | Disadvantages |   
|---|---|
|   Possibility of processing input of any length | Computation being slow  |  
| Model size not increasing with size of input  |  Difficulty of accessing information from a long time ago |   
|  Weights are shared across time |  Cannot consider any future input for the current state | 


## References
1.<https://stanford.edu/~shervine/teaching/cs-230/cheatsheet-recurrent-neural-networks>