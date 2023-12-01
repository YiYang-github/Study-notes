### CS 330: Deep Multi-Task and Meta Learning

**Offered by**: [Prof. Chelsea Finn, Stanford](https://cs330.stanford.edu/) - Fall 2023

**Status**: _Updating..._

#### Warmup Homework 0
**Due Date**: 2023-12-01

**HW1 Insights and Code Highlights**:

- **Scaled Embedding**: The `ScaledEmbedding` proves to be significantly more effective compared to the basic `torch.nn.Embedding`. It demonstrates an improved approach to handling embeddings in deep learning models.

- **Module List Usage**: Implementing `torch.nn.Modulelist([nn_module])` showcases an efficient way to manage multiple neural network modules within a single list structure.

- **Embedding Query**: The embeddings are accessed using `self.U(user_ids)`, providing a straightforward method for querying user-specific embeddings.

- **Key Insight on Multi-Task Learning**: The essence of multi-task learning lies in learning similar representation information. In the code, simply using weights to signify the importance of each task is inadequate. This is because the relationships described by different tasks also have similarities. A more nuanced approach is needed to effectively capture these shared aspects in multi-task learning frameworks.
