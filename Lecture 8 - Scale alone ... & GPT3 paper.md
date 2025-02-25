This lecture contains two paper presentations
***
## Paper 1: Scale Alone Does not Improve Mechanistic Interpretability in Vision Models

Paper pdf: [[Scale Alone Does not Improve Mechanistic Interpretability in Vision Models.pdf]]

Link: https://arxiv.org/abs/2307.05471

Presentation Slides: [[Slides - Scale Alone Does not Improve Mechanistic Interpretability in Vision Models.pdf]]

> [!PDF|255, 255, 0] [[Scale Alone Does not Improve Mechanistic Interpretability in Vision Models.pdf#page=1&selection=82,0,98,93|Scale Alone Does not Improve Mechanistic Interpretability in Vision Models, p.1]]
>  Has scaling models in terms of their dataset and model size improved interpretability? A. We perform a large-scale psychophysics experiment to investigate the interpretability of nine networks through the two most-used mechanistic interpretability methods. B. We see that scaling has not led to increased interpretability. Therefore, we argue that one has to explicitly optimize models to be interpretable. C. We expect our dataset to enable building automated measures for quantifying the interpretability of models and, thus, bootstrap the development of more interpretable models.

> [!PDF|67, 122, 0] [[Scale Alone Does not Improve Mechanistic Interpretability in Vision Models.pdf#page=1&annotation=1145R|Scale Alone Does not Improve Mechanistic Interpretability in Vision Models, p.1]]
> We use a psychophysical paradigm to quantify one form of mechanistic interpretability for a diverse suite of nine models and find no scaling effect for interpretability — neither for model nor dataset size. Specifically, none of the investigated state-of-the-art models are easier to interpret than the GoogLeNet model from almost a decade ago. Latest-generation vision models appear even less interpretable than older architectures, hinting at a regression rather than improvement, with modern models sacrificing interpretability for accuracy. These results highlight the need for models explicitly designed to be mechanistically interpretable and the need for more helpful interpretability methods to increase our understanding of networks at an atomic level. 

> [!PDF|122, 184, 255] [[Scale Alone Does not Improve Mechanistic Interpretability in Vision Models.pdf#page=2&annotation=1174R|Scale Alone Does not Improve Mechanistic Interpretability in Vision Models, p.2]]
> Mechanistic interpretability [37  ] is an emerging branch of explainable AI (XAI) focused on understanding the internal information processing of deep neural networks, possibly by focusing on individual units as their atomic building blocks.

> [!PDF|67, 122, 0] [[Scale Alone Does not Improve Mechanistic Interpretability in Vision Models.pdf#page=2&annotation=1228R|Scale Alone Does not Improve Mechanistic Interpretability in Vision Models, p.2]]
> While scaling models and datasets has fuelled the progress made on many research frontiers [7,  19,  25  ], it does not improve the mechanistic interpretability of individual units. Neither scale nor the other design choices make individual units more interpretable on their own.

> [!PDF|255, 208, 0] [[Scale Alone Does not Improve Mechanistic Interpretability in Vision Models.pdf#page=2&annotation=1231R|Scale Alone Does not Improve Mechanistic Interpretability in Vision Models, p.2]]
> As our study shows, new model design choices or training objectives are needed to  explicitly  improve the mechanistic interpretability of vision models.

##### **Def.** Feature visualization.
> ([[Scale Alone Does not Improve Mechanistic Interpretability in Vision Models.pdf#page=4&annotation=1335R|Scale Alone Does not Improve Mechanistic Interpretability in Vision Models, p.4]])
> Feature visualization describes the process of synthesizing maximally activating images through gradient ascent on a unit’s activation.


![[Screenshot 2025-02-25 at 1.33.31 PM.png]]

![[Screenshot 2025-02-25 at 1.34.52 PM.png|600]]

![[Screenshot 2025-02-25 at 1.31.02 PM.png|500]]
 
#####  Experiment: 2-Alternative-Forced-Choice (2-AFC) 
![[Scale Alone Does not Improve Mechanistic Interpretability in Vision Models.pdf#page=4&rect=97,602,514,725|Scale Alone Does not Improve Mechanistic Interpretability in Vision Models, p.4]]
### Measure of interpretability: 
==A random neuron is chosen. For this neuron, 20 images (synthetic or from dataset) are considered as shown above. The 9 on the right are the ones that activate the neuron and the 9 on left are chosen to not activate the neuron. These activations and non-activates are done at different degrees and that determines the difficulty of the task. A human is asked to choose one image among the two images at the centre. One of these images correspond to the right category (aka. images that activate the neuron in question). In this measure, the more accurately the human can choose the correct image in the centre, the more interpretable that neuron (and hence the model) is. This is how the interpretability of the different models is measured.==

![[Screenshot 2025-02-25 at 1.38.03 PM.png|600]]

### Results:
1. Does scaling models improve interpretability? No--based on the graph below.
![[Screenshot 2025-02-25 at 1.41.06 PM.png|600]]
2. - The graph blow shows the synthetic feature visualization technique was **not** helpful. Natural images give a better result.
![[Screenshot 2025-02-25 at 1.54.04 PM.png]]
3. - Is any specific layer a stronger predictor of interpretability? Somewhat--based on the graph below.
![[Screenshot 2025-02-25 at 1.55.53 PM.png]]
4. Task difficulty (changing the degree at which we activate neurons) does affect interpretability.
![[Screenshot 2025-02-25 at 1.56.41 PM.png]]
### IMI - A dataset to learn automated interpretability measure
https://zenodo.org/records/8131197


Relevant other sources on XAI (explainable AI): [[Explainable Artificial Intelligence (XAI) 2.0- A manifesto of open challenges and interdisciplinary research directions.pdf]]


## Paper 2: Language Models are Few-Shot Learners

Paper pdf: [[Language models are few shot learner.pdf]]
Link: https://arxiv.org/abs/2005.14165

![[Screenshot 2025-02-25 at 2.25.22 PM.png]]
![[Screenshot 2025-02-25 at 2.25.49 PM.png]]
![[Screenshot 2025-02-25 at 2.24.58 PM.png|600]]
![[Screenshot 2025-02-25 at 2.27.17 PM.png|600]]
![[Screenshot 2025-02-25 at 2.33.33 PM.png]]
