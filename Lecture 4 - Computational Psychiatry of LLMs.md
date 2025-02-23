Presentation on personality evaluations of LLMs and FoMo's
***
## Resources:

- [Resources](https://sites.google.com/view/winter2024-towards-agi-course/topicspapers/comppsych-fomo)
- [ComPsy-FoMo Workshop](https://sites.google.com/mila.quebec/compsy-fomo-cerc-aai-workshop/home)
## Introduction
Do LLMs have personalities? Can we apply personality human tests on LLMs? Does it make sense? 

![[Screenshot 2025-02-22 at 5.16.53 PM.png|500]]

We observe that changing the scale of the model can affect its personality traits.

![[Screenshot 2025-02-22 at 5.18.24 PM.png]]
![[Screenshot 2025-02-22 at 5.25.01 PM.png]]


Sparse autoencoders (SAEs) help identify which neurons correspond to specific traits in LLMs by looking into neural activations that strongly align with human-interpretable concepts like compassion. By analyzing these activations, SAEs can pinpoint the neural patterns responsible for personality traits. Once identified, these traits can be **steered** by increasing activation to enhance a trait (e.g. making an LLM more compassionate) or decreasing activation to suppress it (e.g. reducing agreeableness). This enables us to control and study personality of LLMs.
![[Screenshot 2025-02-22 at 5.32.17 PM.png]]

The following graph shows the top 100 compassionate features:
![[Screenshot 2025-02-22 at 5.32.41 PM.png]]


## Appendix
#### Review of Sparse Auto-encoders (SAEs):

Sparse autoencoders help to interpret neural networks. They are a type of autoencoders used in deep learning, primarily for feature learning and dimensionality reduction. Sparse autoencoders add a sparsity constraint to regular autoencoders, which forces the hidden units to activate only a small number of neurons at a time. This encourages the network to discover more meaningful and interpretable features. 

Lecture notes on Sparse Autoencoders: [[Sparse Autoencoders.pdf]] (starts on page 12)



