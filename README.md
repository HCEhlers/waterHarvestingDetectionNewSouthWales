# Project
This project is done in conenction with the Jetson AI Fundamentals course, https://developer.nvidia.com/embedded/learn/jetson-ai-certification-programs#course\_outline.

The aim of the project is to train a model that can predict - given a satellite image of agricultural areas - whether the sattelite image is a reservoir, reservoir with a dead spot
or a reservoir without a dead spot. The value of detecting water harvests autonomously (water extracted from rivers to private reservoirs) can significantly enhance water authorities' capabilities to detect potential water users in remote regions.   


## To Do
- Gennemgå notebooks/videoer i nvidia kurset (H)
- Forbered data til pytorch, label (nvidia classification) data CHECK
- Find frem til model (fx ResNet18-network) vi skal bruge CHECK
- Det skal være reproducerbart, alt skal dokumenteres (H)
- Classification project (H)
- Describe use of Cogniflow.ai for labelling data (R)
- Document assumptions used in labelling (R)
- Future work could estimation of water storage + sensor combination (R)
### Dependencies
- Clone the repository.
- Setup the environment with the .yaml-file that has all the dependencies.
- Then open jupyter lab and run the different notebooks.

```bash
    conda env create -f  waterHarvestingDetectionNewSouthWales.yml
    conda activate waterHarvestingDetectionNewSouthWales
    jupyter-lab
```

The notebook folder contains all the code for the data analysis.
