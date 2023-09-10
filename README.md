# BAM
Bidirectional Associative Memory (BAM) is a type of neural network or associative memory model that can store and retrieve paired associations. It's a symmetric network that can recall patterns in both forward and reverse directions. BAMs are a type of autoassociative memory, meaning they can recall an entire pattern from a partial or noisy input.

Here's a brief overview of how a Bidirectional Associative Memory works:

1. **Memory Storage:** In a BAM, you start by storing pairs of patterns. These pairs consist of an input pattern and its corresponding target or output pattern. For example, you might store pairs like (input_pattern_1, target_pattern_1), (input_pattern_2, target_pattern_2), and so on.

2. **Associative Recall:** Once the patterns are stored, the BAM can recall an entire pattern by presenting only a partial or noisy version of one of the patterns (either the input or the target).

3. **Recall Process:** The recall process occurs bidirectionally. If you present a partial or noisy version of the input pattern, the BAM will retrieve the corresponding target pattern. Similarly, if you present a partial or noisy version of the target pattern, the BAM will retrieve the associated input pattern.

4. **Symmetric Activation:** BAMs use a symmetric activation function, meaning the activation of neurons is influenced by both the input and output sides of the network.

5. **Iterative Process:** The recall process can be iterative, with the network repeatedly updating its activations until it stabilizes on a stable pattern.

BAMs are used in various applications, including pattern recognition, associative memory, and content-addressable memory systems. They are known for their bidirectional retrieval capabilities and ability to handle noisy or incomplete patterns.

Please note that while BAMs are a classic model of associative memory, more advanced neural network architectures, such as deep learning networks, are commonly used in modern applications for tasks like image recognition and natural language processing.
