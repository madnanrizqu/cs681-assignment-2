- Use pretrained embeddings

<!-- most news are done. while imdb waiting for use pretrained embeddings later to faster experiment speed -->
For each dataset:
    For each embedding method:
        - Change to use ANN with tensorflow
            + input layers (DONE)
            + hidden layer with Relu (DONE)
            + output with sigmoid (DONE)
            + use binary cross entropy (DONE)
            + init weights with appropriate method (DONE)
            + compare with/without early stopping (DONE)
            + compare with/without dropout (DONE)
            + compare with/without regularization (DONE)
            + compare with/without batch normalization (DONE)
        - evaluation
            + collect accuracy, precision, recall and F1 Score (IN PROGRESS)
            + visualize using confusion matrices and plots

- compare results of different embeddings methods. reason why some perform better 
