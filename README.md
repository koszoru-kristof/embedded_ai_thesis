# Master's Thesis in the field of Embedded Machine Learning
This repository contains the LaTeX project for `Acoustic Information for Multisensory Occupancy Detection using Machine Learning` Master's thesis. A complete PDF version of the thesis can be found under the `_output` directory or through the official Aalto University publication database. ([link](https://aaltodoc.aalto.fi/items/478c9388-68fe-4697-b3f6-768f290d0a3a), [link2](https://urn.fi/URN:NBN:fi:aalto-2021121910859))


## Abstract
In this thesis, the combination of passive infrared (PIR) and audio sensors for indoor room occupancy detection was demonstrated, with a special focus on audio signal processing and feature extraction using Machine Learning techniques. The lighting automation industry uses extensively PIR or motion sensors for presence detection due to their simplicity and low cost, but their small sensitivity for subtle movements makes them inefficient in certain situations. The occasional undesired behavior is often compensated with long timeout values but this leads to excessive energy consumption.


We are presenting a computationally efficient audio feature extraction method and using exhaustive grid search for Machine Learning model architecture optimization. The best-performing models provided the basis for the embedded implementation of a real-time occupancy device, which combines audio and PIR information for improved presence detection. The prototype performance was measured against the traditional PIR based solutions demonstrating lower false-negative predictions with shorter timeout values.