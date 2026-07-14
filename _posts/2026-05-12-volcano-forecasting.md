---
layout: default
title: "Geophysical Time Series Forecasting at Piton de la Fournaise"
date: 2026-05-12
category: professional
---

# Geophysical time series forecasting at the Piton de la Fournaise volcano by machine learning

> **Authors:** Matthieu Nougaret, Charles Le Losq, Lise Retailleau, Aline Peltier.  
> **Journal:** *Comptes Rendus. Géoscience*, Volume 358 (2026), pp. 283-307.  
> **DOI:** [10.5802/crgeos.335](https://doi.org/10.5802/crgeos.335)

* [View the publication](https://comptes-rendus.academie-sciences.fr/geoscience/articles/10.5802/crgeos.335/)
* [View Source Code on GitHub](https://github.com/MatthieuNougaret/Predicting-geophysical-time-series-on-volcano-at-Piton-de-la-Fournaise)

---

### Abstract:

This study evaluates the potential of machine learning approaches to forecast the daily volcano-tectonic seismicity and GNSS deformation data that are used to monitor the active Piton de la Fournaise volcano (La Réunion Island, France). We tested six different methods to forecast the next five days of the geophysical signals: a naive baseline method, a linear regression model, and four different artificial neural network models including feed-forward, 1D convolutional, LSTM and Transformer architectures. All machine learning models performed better than the baseline. Auto-regressive Transformer models performed best for seismicity, while Linear models proved to be quite effective for GNSS data. Combining seismicity and GNSS datasets was not key to achieving better results. We also tested the GARCH model, a statistical econometric method. It shows no advantage in handling volatility and, like ML models, fails to anticipate sharp pre-eruptive accelerations.

Results underscore the challenges of forecasting low-signal, non-cyclic volatile volcanic time series. The data we used may not contain all the necessary information for their own forecasting. Future developments may explore the addition of other data types, feature engineering, data generation, hybrid models and transfer learning. Those developments are important because machine learning models remain promising as complementary tools to existing volcano monitoring strategies.


[Back to Home](/)