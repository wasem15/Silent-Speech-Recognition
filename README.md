# Silent Speech Recognition — EMG Preprocessing

Research notebook for preprocessing electromyography (EMG) signals for silent-speech recognition.

The notebook focuses on preparing biosignal data for downstream machine-learning experiments: visualization, filtering, normalization, segmentation, and exploratory feature preparation.

## Research workflow

~~~text
Raw EMG signal
      │
      ▼
Signal inspection
      │
      ▼
Band-pass filtering
      │
      ▼
Normalization
      │
      ▼
Window segmentation
      │
      ▼
Feature preparation
      │
      ▼
ML-ready data
~~~

## What is covered

- Time-series visualization
- Signal distribution analysis
- Frequency-domain / spectrogram inspection
- Band-pass filtering
- Normalization
- Overlapping signal-window generation
- Data preparation for subsequent classification experiments

## Technology

- Python
- Jupyter Notebook
- NumPy / pandas-style numerical workflows
- Matplotlib
- SciPy-style signal-processing workflows

The notebook itself is the primary research artifact; exact experiment outputs depend on the dataset and execution environment.

## Repository structure

~~~text
.
├── ssr-data-preprocessing.ipynb
├── README.md
└── LICENSE
~~~

## How to run

1. Create a Python environment.
2. Install the notebook's dependencies.
3. Open the notebook in Jupyter.
4. Run the preprocessing cells in order.

## Research context

This repository is the preprocessing stage of a broader silent-speech recognition exploration. A separate repository contains a neural-network classification experiment using processed EMG signals.

## Limitations

Signal-processing and model performance depend strongly on the quality, labeling, and collection protocol of the EMG dataset. Notebook results should therefore be interpreted as experimental rather than production-ready.

## License

Apache License 2.0.
