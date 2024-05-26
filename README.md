# Partitioned Angle-based Encoding for Quantum Convolutional Filters
In this notebook, I explore a novel approach to encoding input features into rotation angles by partitioning regions extracted by an unfolding function into subsets and encoding each subset into the available qubits. 

1. **General Quantum Convolutional Layers**:
- Quantum convolutional layers have been proposed and implemented in various forms, 
but they often follow more straightforward encoding schemes where the input data is directly mapped 
onto quantum states without sophisticated partitioning strategies.

- Standard implementations, such as the one you provided using Pennylane, typically focus on encoding small, fixed-size regions directly onto qubits.

2. **Partitioning for Efficient Encoding**:

- The idea of partitioning input regions into subsets to be encoded onto different qubits introduces a level of parallelism and scalability that is less common in typical quantum convolutional layer implementations.

- This approach allows for handling larger input sizes and utilizing a limited number of qubits more effectively, which is particularly valuable given the current hardware constraints in quantum computing.
