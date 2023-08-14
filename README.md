# Carcinoma Classification - OxML 2023 MLx Cases

## Competition info
In this competition, the goal was to classify `HES stained histopathological slices` as containing or not containing carcinoma cells. If a carcinoma is present, it is also possible to tell whether it is malignant or not, which gives us three classes:

Carcinoma neg (-1)
Carcinoma pos, benign (0)
Carcinoma pos, malignant (1)

A total of 186 images was provided but *labels were only present for **62** of them*.

## Models - Results

Two different architectures were used. The first is an `Inception ResNet v2` CNN with the bottom layers frozen and the second was a `zero-shot model` from Open Clip. Both models achieved a score of **77.419%** on the *public test set* and **70.967%** on the *private test set*.
