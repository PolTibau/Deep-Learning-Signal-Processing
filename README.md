# Deep Learning and Signal Processing

Lab deliverables for the course *Deep Learning and Signal Processing*, part of the
Master MVA (Mathématiques, Vision, Apprentissage), 2026-2027.

Authors: **Pol Tibau Rubau** and **Pablo Borrego**.

## About the course

The course explores what deep learning can bring to signal processing through industrial
use cases such as radar emitter identification, signal detection for cognitive radio,
speaker recognition, restoration of degraded audio signals and predictive maintenance.
For each use case, "classical" signal processing pipelines are implemented in lab sessions
and then revisited with a learning-based approach, after introducing the operational
context and modelling the physics of the problem.

The theory covers signal processing tools (time-frequency and time-scale representations,
filtering) and machine learning (supervised and unsupervised learning, classification and
clustering algorithms, optimization and gradient descent, deep learning fundamentals and
the main neural network architectures), around the question *"what makes deep learning
deep?"*.

## Labs

| Notebook | Contents |
|---|---|
| [`TP1_Tibau_Borrego.ipynb`](labs/TP1_Tibau_Borrego.ipynb) | **Part 1 – Audio:** visualization of an audio signal and pitch computation. **Part 2 – Pulse detection:** two detection methods and their comparison |

## Running the notebooks

Dependencies: `numpy`, `scipy`, `matplotlib`.

The audio signal of Part 1 is embedded in the notebook. Part 2 loads
`signaux_impulsions.npz`, provided with the course and not included in this repository:
place it next to the notebook before running it.

The lab statements were provided by the teaching team.
