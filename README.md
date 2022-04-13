# speech recognition practice

## Tools and Libraries

- Python==3.6
- Keras==2.3.1
- Tensorflow==1.14.0
- Numpy==1.17.4
- Matplotlib==3.2.1
- librosa==0.8.1
- sklearn==0.21.3

## data minining:
- supervised
    - teach or train the machine using data that is well labeled, which means some data is already tagged with correct answer.
    - after that, the machine is provided with new set of examples(data) so that supervised learning algorithm analyses the training data(set of trainning example) and produces a correct outcome from labeled data.
    - types:
        - regression
        - logistic regression
        - classification
        - Naive Bayes Classifier
        - K-NN
        - Decision tree
        - SVM
   - pros:
        - allows collecting data and produces data output from previous experiences.
        - helps to optimize performance criteria with the help of experience
        - helps to solve various types of real-world computation problems
   - cons:
        - classifying big data can be challenging.
        - training for supervised learning needs a lot of computation time, so it requires a lot of time.
- unsupervised
    - traning of a machine using information that is neither classfied or labeled and allowing the algorithm to act on that information without guidance.
    - Here the task of the machine is to group unsorted information according to similarities, patterns, and differences without any prior training of data.
    - is classified into two categories of algorithms:
        - clustering:
            - a clustering problem is where you want to discover the inherent groupings in the dataa, such as grouping customers by purchasing behavior.
        - clustering: 
            - Exclusive(partitioning)
            - agglomerative
            - overlapping
            - probabilistic
        - clustering types:
            - hieraachical clustering
            - k-mean clustering
            - principal component analysis
            - singular value decomposition
            - independent component analysis
        - association:
            - an association rule learning problem is where you want to discover rule that describe large portions of your data, such as people that buy X also tend to buy Y.
            
- reinforcement 
    - an area of ML.
    - it is about taking suitable action to maximize reward in a particular situation
    - it is employed by various software and machines to find the best possible behavior or path it should take in a specific situation.
    - there is no answer key for RL, but the reinforcement agent decides what to do to perform the given task. in the absent of a training dataset, it is bound to learn from experiences.
    - main points in RL:
        - input: should be an initial state from which the model will start
        - output: there are many possible outputs as there are a variety of solutions to a particular problem
        - training: the training is based upon the input, the model will return a state and the user will decide to reward or punish the model based on its ouput
        - the model keeps continues to learn
        - the best solution is decided based on maximum reward
    - Types of Reinforcement:
        - Positive:
            - defined as when an event, occurs due to a particular behavior, increases the strength and the frequency of the behavior. In other words, it has a positive effect on behavior.
            - Pros:
                - maximizes performance
                - sustain change for a long period of time
                - too much reinforcement can lead to an overload of states which can diminish the results.
       - Negative:
            - defined as strengthening of behavior because a negative condition is stopped or avoid.
            - Pros:
                - increases Behavior
                - provide defiance to a minimum standard of performance
                - only provides enough to meet up the minimum behavior
    - applications:    
        - used in robotic for industrial automation
        - used in ML and data processing
        - used to create training systems that provide custom instruction and materials according to the requirement of students.
    - RL can be used in large environments in the following situations:
        - a model of the environment is known, but an analytic solution is not available;
        - only a simulation model of the environment is given( the subject of simulation-based optimization)
        - the only way to collect information about the environment is to interact with it.


### Feature engineering
- imputation
- scaling
- extracting date
- binning
- one-hot encode



## Credit
Forgot 
