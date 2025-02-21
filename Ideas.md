Ideas for the BP generalization:
1. Using something similar to MAML for learning some sort of model to adapt to new subjects quickly with some images of the new subject, but without labels of the new subject. Basically doing the last step of MAML where we predict future fine-tuning for the beginning of the model that looks at the images. It can also be using the images to fine tune a model that reads some landmarks on the face.
2. using ideas for matching networks where we let the new subject use info from the other models to quickly learn to adapt to new subjects.
3. use contrastive learning but forcing different subjects with similar BP range to come closer and similar subjects with different BP range to get further apart in the representation.
4. Use Image perturbations to augment the dataset with new variations of video data of the subjects and train on them.
5. Instead of feeding absolute frames, pass frame differences to the model. To avoid noise, we can feed the frame differences alog with the frame values to put the changes in RGB in context of the current RGB values. 
6. use different image formats other than RGB to focus more on the changes and less on brightness.
7. 