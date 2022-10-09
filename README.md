# QProject: A Step into Primary Research with Quantum Computing and Qiskit (29 Oct, 2022 - 20 Jan,2023)
QIran's QProject101 (IR_QProject_101) is a **12 week** long research program designed for the students and newcomers to the field of quantum computing and quantum programming. The main purpose of this program is to get acquainted with elementary research projects and utilize Qiskit skills to perform real world problems on a quantum computer. Some of the topics covered in the topics include Quantum Teleportation, Variational Quantum Eigensolver, Quantum Image Processing, Quantum Generative Adversarial Networks, Quantum Random Walks, Quantum Key Distribution, Quantum Game Theory , and Exploration of Superconducting Quantum Hardware. The program has **9 topics** and with **5 mentors**. Researchers/students are mentored to tackle different challenges and prepare reports on their progress.

Please read the whole document before asking any questions. You may join the discord server of QIran to connect with us directly.
The following represents the description of each research project.

### #01: Bidirectional Controlled Hybrid Protocol of Quantum Teleportation and Remote State Preparation (RSP)

**Level:** Intermediate

**Number of Group Members:** 2-3

**Mentor:** Payman Kazemikhah

**Pre-requisite:** Quantum Computing/ Quantum Teleportation/ Qiskit

**Abstract:** Quantum teleportation (QT) allows the transmission of unknown quantum states between two nodes in a quantum network. QT utilizes quantum channel (Entangled qubits) and classical channel (conventional bits) to transmit the information. If the information transmission works at both ends and at the same time, the protocol is considered as bidirectional quantum teleportation (BQT). Moreover, if the teleportation happens under the supervision of a third party, the protocol is called controlled quantum teleportation (CQT). Remote state preparation (RSP) is another quantum communication protocol in which a quantum state is prepared remotely and the information is not unknown.
The final goal is to design a hybrid controlled protocol of quantum teleportation and remote state preparation. In this protocol, sender (Alice) tends to transmit an unknown quantum state to a receiver (Bob). At the same time, Bob wants to prepare a predefined and known quantum state to Alice, remotely. The whole information transmission occurs only when the supervisor, i.e. Charlie (the controller) inform his consent and allows the transmission of information.

### #02: A Survey for Designing a Superconducting Quantum Device/Chip using Open-Source Packages

**Level:** Intermediate

**Number of Group Members:** 4-5

**Mentor:** Payman Kazemikhah

**Pre-requisite:** Superconductive Qubits / Quantum Computers / Python / (Appropriate for Bachelor or Master Students in Physics and Electrical Eng.)

**Abstract:** Superconducting qubits are one of the most mature technologies to make quantum computers a reality. They’re considered as one of the frontrummers to build quantum processors. Gladly, students can use software packages to design/optimize relevant devices/chips to this technology. The provided open-source packages allow students to design qubits, resonators, control and read-out circuits. Moreover, you can see the results and characteristics of your simulated device using coding and workflows.
The goal of the research is to investigate the open-source and accessible software packages for designing superconductive technology. The group members must go through all of the libraries and options to examine the full potential of each package. The four developed packages for superconductive qubits are the following:
1. Qiskit Metal (IBM Company)
2. KQCircuits (IQM Company)
3. SQCircuit (Stanford University)
4. scQubits (University of Chicago)
After acquainted with the basics of superconductive qubits, the group members must get to know each package and try to present simple codes and workflows required to design the devices. Then, provide a detailed report of the functionality and the features of each software package.

### #03: Quantum Image Processing and Representation

**Level:** Intermediate

**Number of Group Members:** 3 

**Mentor:** Armin Ahmadkhaniha

**Prerequisite:**
1-Linear Algebra
2- Qbronze (simulation and visualization of quantum circuits in Qiskit)
3-Classic Image Processing

**Abstract:**
In this project, We will study Quantum image processing as one of the highly used fields in AI. Quantum image processing applications in face recognition and autonomous vehicles are undeniable. Hence, finding quantum counterparts such as the Qsobel (edge detection algorithm) for classical algorithms could speed up quantum image processing affairs.
We are going to evaluate participants’ skills in implementing and analysis of quantum circuits based on quantum image processing algorithms. Furthermore, the noise effect and its result for image representation will be studied. 

### #04: Comparison of the EQGAN and QGAN as Quantum Counterparts for Generative Machine Learning Algorithm

**Level:** Advanced

**Number of Group Members:** 4 or 5

**Mentor:** Armin Ahmadkhaniha

**Prerequisite:**
1-Machine Learning
2- ML in Python
3-GAN (Generative Adversarial Network) performance
*4-QML (basic information)

**Abstract:**
In this project, We will study GANs consisting of two neural networks (Generator and Discriminator) contesting with each other in a game in the form of a zero-sum game, where one agent's gain is another agent's loss. Given a training set, this technique learns to generate new data with the same statistics as the training set. For example, a GAN trained on photographs can generate new photographs that look at least superficially authentic to human observers, having many realistic characteristics. The QGAN and EQGAN are two quantum models for generating new data that are employed for further investigation in this project.
We are going to evaluate participants’ skills in implementing and analysis of quantum circuits based on QGAN and EQGAN. Furthermore, the noise effect and its results will be studied by tuning learning hyperparameters. 

### #05: A survey for Variational Quantum Eigensolver (VQE) as a promising quantum algorithm in NISQ era and beyond.

**Level:** Intermediate

**Number of Group Members:** 2-3

**Mentor:** Abbas (Omid) Hassasfar

**Prerequisite:**
1-Linear Algebra
2- Qbronze (simulation and visualization of quantum circuits in Qiskit) or equivalent
3- Basics knowledge of Quantum Mechanics

**Abstract:**
The Variational Quantum Eigensolver (VQE) is a flagship algorithm for quantum chemistry using near-term quantum computers.
The inputs to the VQE algorithm are a molecular Hamiltonian and a parametrized circuit preparing the quantum state of the molecule. Within VQE, the cost function is defined as the expectation value of the Hamiltonian computed in the trial state. The ground state of the target Hamiltonian is obtained by performing an iterative minimization of the cost function. The optimization is carried out by a classical optimizer which leverages a quantum computer to evaluate the cost function and calculate its gradient at each optimization step.
The aim of this project is to calculate the bond length and energy of the ground state (and in the next phases, the energy of the excited states) of the system by considering the desired Hamiltonian and the parameters of the quantum circuit and the initial state.

### #06: One and two-dimensional Quantum Walk Optimization Using Initial State Phase Design of State Qubits

**Level:** Intermediate

**Number of Group Members:** 3

**Mentor:** Hossein Khabazipour

**Prerequisite:**
1- Basic mathematics (linear algebra, vector, matrix and Fourier transform)
2- Quantum computing
3- Basics knowledge of Qiskit
4- Classical random walk and Markov chain

**Abstract:**
Many classical algorithms are based on random walk. Markov chain simulation, which has emerged as a powerful algorithmic tool, is one of such examples. Like the classical random walk, the quantum version has become an important part of quantum algorithms. Quantum walk, as it is known today, is a generalized form of classical random walk, developed using aspects of quantum mechanics such as superposition and interference of quantum domains.
The concept of quantum walk has been developed and is now studied in two standard ways:
Continuous time quantum walk model (CTQWM) and discrete time quantum walk model (DTQWM). A special type of discrete-time quantum walk known as Hadamard is used in this project.
The aim of this project is to design a coin-base Hadamard quantum walk system for optimal search in a one- and two-dimensional network with an arbitrary number of nodes. First, the relationships and the mathematical model of the problem will be studied, and then the quantum walk model and its effectiveness and efficiency compared to the classical walk will be studied and compared.
At the end, its mathematical model is extracted and the final model is optimized by some algorithms in MATLAB software, and the initial phase of the position qubits will be estimated in such a way that we have the best distribution of probability on different permutations(positions) on the desired network.

### #07: Investigating for the Performance of Quantum Teleportation Protocols for Different Information Bandwidths in a Noisy Environment

**Level:** Intermediate

**Number of Group Members:** 2-3

**Mentor:** Yousef Mafi

**Pre-requisite:** Quantum Computing/ Quantum Teleportation/ Qiskit / Basics of Machine Learning

**Abstract:**
Quantum teleportation (QT) allows the transmission of unknown quantum states between two nodes in a quantum network. QT utilizes quantum channel (Entangled qubits) and classical channel (conventional bits) to transmit the information. If the information transmission works at both ends and at the same time, the protocol is considered as bidirectional quantum teleportation (BQT). Moreover, if the teleportation happens under the supervision of a third party, the protocol is called controlled quantum teleportation (CQT). Quantum information gets teleported to receiver. Thus one can investigate the information bandwidth for different quantum protocols.
The goal of this research is investigation and simulation of information capacity for different protocols. The researchers must study and implement various quantum teleportation protocols. Afterwards, they must utilize machine learning and information bandwidth specs to model the information capacity for the investigated protocols.

### #08: Quantum Key Distribution Protocol Based on the Game Theory (Monty Hall Game)

**Level:** Advanced

**Number of Group Members:** 4

**Mentor:** Yousef Mafi

**Pre-requisite:** Advanced Quantum Computing/ Quantum Key Distribution Protocols (QKD) / Qiskit / Linear Algebra

**Abstract:**
Quantum game theory is an enhanced mathematical and foundational adaptation of the classical game theory. In quantum models, all of the possible paths to decision making extends itself to a complex Hilbert space. The Monty Hall game is one of the probability puzzles in this field. The quantum version of this game exploits quantum entanglement and offers boosted computational advantage. One of the applications of this game is to deploy quantum key distribution (QKD) protocols. 
The goal of this research is investigation and implementation of the of quantum key distribution protocols on Qiskit using Monty Hall game and quantum game theory. 

### #09: Improvement of the Quantum Teleportation Based on the Phase Term of Qubit State

**Level:** Intermediate

**Number of Group Members:** 3-4

**Mentor:** Yousef Mafi

**Pre-requisite:** Quantum Computing/ Quantum Teleportation Protocols

**Abstract:**
Quantum teleportation (QT) allows the transmission of unknown quantum states between two nodes in a quantum network. QT utilizes quantum channel (Entangled qubits) and classical channel (conventional bits) to transmit the information. If the information transmission works at both ends and at the same time, the protocol is considered as bidirectional quantum teleportation (BQT).
Quantum information is encoded in the quantum input state of the sender and gets teleported to receiver side. But in Qiskit simulations we can only measure the magnitude of the quantum state and the local phase of the states are neglected. 
The goal of this research is evaluating and detecting the local phase in quantum states and their effect in teleportation protocols. The local phase in quantum state can help improve the efficiency of the protocols
