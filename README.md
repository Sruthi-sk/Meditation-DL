# meditation-DL
ML and DL methods to distinguish EEG meditation states

Code for paper presented at IEEE ICBNA 2022:
  Simple Neurofeedback via Machine Learning: Challenges in real time multivariate  assessment of meditation state
Dataset: Long-term Vipassana practitioners: multichannel EEG data during Eyes closed Rest, Vipassana meditation, Cognitive Task
Signal processing techniques are used to extract features from EEG data. 
An autoencoder model is then trained on these features such that the model can be run in real time.  Its reconstruction errors or its latent variables are used to provide non typical feedback parameters which are used to establish an objective measure of meditation ability.

