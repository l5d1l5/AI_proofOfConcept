# AI_proofOfConcept
This is a temporary repository demonstrating how a trained algorithms from VIAME can be stored / updated on GitHub. 
The folder structure and constituent files was created automatically by VIAME in the course of annotating imagery, training an algorithm, and implementing a pipeline. Notable folders include: 

- DIVE_Projects includes JSON files recording the imagery annotations (these annotations include both manually annotated data ("train_. . .") as well as the product of implementing a pipeline ("test_. . . ").
- DIVE_Pipelines includes the trained algorithm.
- DIVE_Jobs includes information from the training of the algorithm as well as the implementation of a pipeline, i.e., applying the algorithm to unseen data. 

I have not yet received permission to add the photos used to train and test VIAME that generated the SVM model in this repo, so for now, this repo will simply contain all files associated with the training and testing of an algorithm (minus the imagery). If one had imagery suitable for analysis with this SVM model, one could (1) download VIAME desktop, (2) clone this repository, and (3) copy VIAME batch scripts into that folder. As is, the SVM model here on git is from 100 individuals (mostly urchins) annotated across 80 images, i.e., this SVM model is for proof-of-concept only. 




