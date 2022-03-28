# LSTM-temporal-prediction-for-turbulent-minimal-channels
From the MSc thesis project 'Predicting the temporal dynamics of turbulent channels through deep learning' (arxiv paper pre-print https://arxiv.org/abs/2203.00974 )


The success of recurrent neural networks (RNNs) has been demonstrated in many applications related to turbulence, including flow control, optimization, turbulent features reproduction as well as turbulence prediction and modeling. With this study we aim to assess the capability of these networks to reproduce the temporal evolution of a minimal turbulent channel flow. We first obtain a data-driven model based on a modal decomposition in the Fourier domain (which we denote as FFT-POD) of the time series sampled from the flow. This particular case of turbulent flow allows us to accurately simulate the most relevant coherent structures close to the wall. Long-short-term-memory (LSTM) networks and a Koopman-based framework (KNF) are trained to predict the temporal dynamics of the minimal-channel-flow modes. Tests with different configurations highlight the limits of the KNF method compared to the LSTM, given the complexity of the flow under study. Long-term prediction for LSTM show excellent agreement from the statistical point of view, with errors below 2% for the best models with respect to the reference. Furthermore, the analysis of the chaotic behaviour through the use of the Lyapunov exponents and of the dynamic behaviour through Poincaré maps emphasizes the ability of the LSTM to reproduce the temporal dynamics of turbulence. Alternative reduced-order models (ROMs), based on the identification of different turbulent structures, are explored and they continue to show a good potential in predicting the temporal dynamics of the minimal channel.
