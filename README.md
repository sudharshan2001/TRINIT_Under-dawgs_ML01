# TRINIT_Under-dawgs_ML01

weights can be downloaded from link below and put them in the same folder as trinit-infer.ipynb

https://drive.google.com/file/d/12DYiGZNtz8UMtqma3XSBec44WDwZsOD1/view?usp=share_link

# Requirements
```
matplotlib>=2.2.4
numpy>=1.16.3
librosa>=0.6.3
pescador>=2.0.1
torch>=1.1.0
tqdm>=4.32.1
IPython
```

# Problem Statement

1. Develop a generative model that can create synthetic speech
samples for underrepresented languages and dialects.

2. The model should be able to generate speech samples for both male and female speakers and for different age groups.

# Approach

The language we chose for the audio synthesis is Tamil and we utilized the dataset from Open SLR-Crowdsourced high-quality Tamil multi-speaker speech data set.

We built two models, one is WaveGAN(appraoch 1) based and another is a simple GAN-(appraoch 2) based architecture that mainly consists of Dense Networks.

We only had the time to train 1 epoch on waveGAN which took about 7 hours but it had some screeching noises and the GAN-based architecture had static noises.


