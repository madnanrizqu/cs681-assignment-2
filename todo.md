- Use pretrained embeddings

For each dataset:
    For each embedding method:
        - Change to use ANN with tensorflow
            + input layers
            + hidden layer with Relu
            + output with sigmoid
            + use binary cross entropy
            + init weights with appropriate method
            + compare with/without early stopping
            + compare with/without dropout
            + compare with/without regularization
            + compare with/without batch normalization
        - evaluation
            + collect accuracy, precision, recall and F1 Score
            + visualize using confusion matrices and plots

- compare results of different embeddings methods
