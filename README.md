# Investigating Hallucination in Image Sequences using Mementos

## Experiment Design
We conducted the experiments using the best open source models,
respectively, Chat-UniVi for sequential input and LLaVA-1.5 for combined input as shown in [Mementos paper](https://arxiv.org/abs/2401.10529) <br>

The objective of this study is to examine how data perturbations influence model predictions, with a particular focus on understanding which factors might lead to hallucinations and how much they can affect the model’s response. By addressing these aspects, we aim to understand the model’s sensitivity to temporal information and noise in both text and images. <br>

In addition, we also did explore mitigation hallucination techniques, which are MemVR and HALC. Since both are only accept single image as input, we applied those to combined input only. <br>

1. Sequential <br>
    1.1. Chat-UniVi <br>
    1.2. Incorrect Prompt <br>
    1.3. Incorrect Images (rate=20%, 40%, 60%, 80%) <br>
    1.4. Reduced Images (rate=20%, 40%, 60%, 80%) <br>
    1.5. Shuffled <br>
2. Combined <br>
    2.1. LLaVA1.5 <br>
    2.2. LLaVA1.5 + Incorrect Prompt <br>
    2.3. LLaVA1.5 + MemVR <br>
    2.4. LLaVA1.5 + MemVR + Incorrect Prompt <br>
    2.5. LLaVA1.5 + HALC <br>
    2.6. LLaVA1.5 + HALC + Incorrect Prompt <br>

## Dataset
The dataset of the daily-life images can be found in [Mementos paper](https://arxiv.org/abs/2401.10529) 

## Acknowledgement
We would like to thank our professors, Raffaella Bernardi and Paolo Rota, for their support and guid- ance throughout this project. We would like to thank the University of Trento for providing the resources to work on this research. Thank you to our group members Bruno and Zabrina who worked together to do this project. We would also like to thank all those who helped and supported us in this project.