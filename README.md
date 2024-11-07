This repository contains the code for a GitHub pages site for the publication [Generative Location Modeling for Spatially Aware Object Insertion
](https://arxiv.org/abs/2410.13564). The project page is hosted at https://qualcomm-ai-research.github.io/location-modeling/. 

This project showcases a location model for localized image editing tasks such as object insertion. 
As existing models are based on generic textual instructions , they either 1) insert objects with unrealistic locations and scales or 2) unintentionally alter the scene background.
We instead propose to first explicitly model the plausible locations for an object to be added to a given background scene, and then we use an off-the-shelf inpainting model to render it.
Our location model generates plausible placements by autoregressively decoding bounding box coordinates, and it delivers high quality edits that substantially outperform the state-of-the-art in object insertion.

