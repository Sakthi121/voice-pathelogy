# Voice Pathology Detection Model

## Data Source
The dataset used for this model was compiled by Max Little of the University of Oxford in collaboration with the National Centre for Voice and Speech, Denver, Colorado.

## Attribute Details
- **Patient ID**: Unique identifier for each patient.
- **Jitter (% and Abs)**: Measures cycle-to-cycle variation in fundamental frequency.
- **Jitter:RAP, Jitter:PPQ, Jitter:DDP**: Different variations of jitter calculations.
- **Shimmer (%, dB, APQ3, APQ5, DDA)**: Measures amplitude variation and perturbation in voice.
- **NHR**: Noise-to-harmonics ratio.
- **HNR**: Harmonics-to-noise ratio.
- **RPDE**: Recurrence period density entropy, indicating repetitiveness of the signal.
- **DFA**: Detrended Fluctuation Analysis, assessing signal complexity.
- **Status**: Binary label indicating health status (1 for Parkinson's, 0 for healthy).

## Model Explanation
- Utilizes various speech signal processing algorithms including Time Frequency Features, Mel Frequency Cepstral Coefficients (MFCCs), Wavelet Transform-based Features, Vocal Fold Features, and TWQT features.
- Extracts clinically useful information for Parkinson's Disease (PD) assessment.
- Employs machine learning techniques to analyze and classify voice data, aiding in the detection of voice pathologies such as Parkinson's Disease.

## Objective
Develop a robust model to accurately identify voice pathologies, particularly Parkinson's Disease, using advanced signal processing and machine learning methods.
