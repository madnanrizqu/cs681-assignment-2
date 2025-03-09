- Use pretrained embeddings

For each dataset:
    For each embedding method:
        - Change to use ANN with tensorflow
            + input layers (DONE)
            + hidden layer with Relu (DONE)
            + output with sigmoid (DONE)
            + use binary cross entropy (DONE)
            + init weights with appropriate method
            + compare with/without early stopping
            + compare with/without dropout (DONE with)
            + compare with/without regularization
            + compare with/without batch normalization (DONE with)
        - evaluation
            + collect accuracy, precision, recall and F1 Score (DONE accuracy)
            + visualize using confusion matrices and plots

- compare results of different embeddings methods. reason why some perform better
