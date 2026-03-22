# Project-AI
## Modeling material demand in relation to artificial intelligence demand.

At a time when artificial intelligence (AI) is exploding and becoming the 4th great technological revolution, we are constantly exposed to the energy challenge that comes with it. However, the material aspect is rarely addressed. This study aims to shed light on material consumption required to support the growing demand for AI.

The objective is to model the demand for materials necessary for the proper functioning of generative AI in the near future. The reference AI is ChatGPT 4 (around 17,500 billion parameters). It is important to note that the results concern only the material requirements for the operation of GPU units. Broader infrastructure components, such as networks, storage, and cooling systems, are not taken into account in this analysis.

The GPU chip studied is the NVIDIA A100, used by OpenAI, Meta, and Microsoft. The ChatGPT 4 model will therefore serve as the reference in the calculations, with the assumption that the material consumption of other generative AIs is similar.

In a first part, we will look at the modelling of material requirements relative to AI demand. In a second part, we will analyse the results in light of current material resources, while taking into account geographical, geopolitical, and commercial factors.

I chose to start the model from requests. These requests are nothing more than strings of characters broken down into tokens. These tokens are processed in data centers using FLOPs (number of floating-point operations performed per second). Thus, by establishing the link between requests and the associated number of computations (FLOPs), it becomes possible to work back to the number of GPUs required. From this quantity, we derive the associated material demand.


A large portion of the reference data comes from a single source, which is the following: [1] From FLOPs to Footprints: The Resource Cost of Artificial Intelligence; Sophia Falk, Nicholas Kluge Correa, Sasha Luccioni, Lisa Biber-Freudenberger, and Aimee van Wynsberghe; December 3, 2025.
