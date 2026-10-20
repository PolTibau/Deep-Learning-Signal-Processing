# Deep Learning and Signal Processing

Lab deliverables for the course *Deep Learning and Signal Processing*, part of the
Master MVA (Mathématiques, Vision, Apprentissage), 2026-2027.

## About the course

Lab work for a course on deep learning applied to signal processing. Each lab compares a classical pipeline with a learning-based approach on an industrial use case (radar emitter identification, cognitive radio signal detection, speaker recognition, audio restoration, predictive maintenance). Theory covers time-frequency representations, filtering, classical machine learning and deep learning architectures.

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
