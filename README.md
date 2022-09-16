# Using Quantum Neural Networks to Identify Tetris Blocks
2022 TJ Senior Research Project
(tetris image dataset will be uploaded soon)
This project was done in my senior year at TJHSST, in the Quantum Physics and Optics Lab. My lab partner, Adnan Murtaza and I had a keen interest in quantum computing and wanted to investigate how we could create quantum versions of neural network, and how machine learning could be combined with quantum computing. The quantum neural network isn't a traditional network; instead it is a series of quantum gates that take qubits as input and manipulate the data, eventually resulting in a readout bit with an output. We used the network structure created by tensorflow quantum, but created our own dataset of 4x4 Tetris images to run the network on. We achieved a 98% accuracy rate, but the network is very limited compared to its conventional counterpart: the output is binary, so only 2 unique Tetris images can be used as outputs. As more advancements are made in quantum computing, we can hopefully expand the network to multiary outputs.

![image](https://user-images.githubusercontent.com/107822939/190576919-d8893521-9577-47f9-8797-06d4d570b1a5.png)


Sources: 
https://www.tensorflow.org/quantum/tutorials/qcnn
https://arxiv.org/abs/2003.02989
