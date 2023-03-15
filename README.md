# Halloween_costume

What is this?
An AI that will guess your halloween costume! More specifically, a program that will match images of halloween costumes to 5,000 pre-defined possible halloween costumes.

How does this work?
The program uses CLIP to calculate a similarity score between the uploaded image and every halloween costume idea in this dataset. CLIP is doing zero-shot image classification over a dataset of 5,000 halloween costume ideas. Unfortunately if your costume is not in the dataset this program will be unable to guess your costume correctly, though it might still find an example in the dataset that is a decent match for your costume.
