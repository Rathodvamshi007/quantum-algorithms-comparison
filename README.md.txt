Quantum Algorithms Demo
=======================

A Jupyter Notebook demonstrating three foundational quantum algorithms:
1. Quantum Teleportation
2. Deutsch-Jozsa Algorithm
3. Grover's Search Algorithm



Description
-----------
This project simulates three key quantum algorithms using Qiskit. Each algorithm showcases a unique quantum advantage:
- Teleportation: Transfers quantum states using entanglement.
- Deutsch-Jozsa: Determines if a function is constant or balanced with one query.
- Grover's Search: Searches an unstructured database quadratically faster than classical methods.

---

Setup
-----
1. Install dependencies by running:
   pip install -r requirements.txt

2. Run the Jupyter Notebook with:
   jupyter notebook notebooks/quantum_algorithms.ipynb

---

Results
-------
- Teleportation: Bob's qubit matches Alice's original state.
- Deutsch-Jozsa: Distinguishes constant and balanced functions.
- Grover's Search: Amplifies the probability of measuring the solution.

---

Project Structure
-----------------
quantum-algorithms-demo/
├── README.txt
├── LICENSE
├── requirements.txt
└── notebooks/
    └── quantum_algorithms.ipynb

---

License
-------
This project is licensed under the MIT License.


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/Rathodvamshi007/quantum-algorithms-comparison/blob/main/quantum_algorithms.ipynb)
