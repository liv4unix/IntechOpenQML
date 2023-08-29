# IntechOpenQML
This is the Repository containing the IBM Quantum Cloud Jupyter Notebook for the IntechOpen QML Book Chapter.

### This Notebook is premised on IBM's original QGAN work, found here:<br>
<a href="https://learn.qiskit.org/course/machine-learning/quantum-generative-adversarial-networks"> Building Quantum Generative Adversarial Networks with IBM Qiskit </a>
<br>
### The Experiment section of the QML Chapter of the Book updates IBM's original and now deprecated QGAN work as follows:<br>
1) Implements IBM's newest Quantum Sampler Algorithm (launched May 2023) <br>
2) Implmenets a backend IBM SamplerAER Noise model to make it more difficult for the quantum generator and quantum discriminator to detect and correct superconducting-NISQ quantum errors <br>
3) Optimizes the Tensorflow Hyperparameters for both the QGAN generator and discriminator
