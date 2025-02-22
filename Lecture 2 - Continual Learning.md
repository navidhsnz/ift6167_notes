
---

#Paper: Start of the field: [[Empirical Investigation of Catastrophic Forgetting-goodfellow.pdf]]
#Paper:  [[Continual Lifelong Learning with Neural Networks.pdf]]

---
![[Screenshot 2025-02-20 at 3.24.42 PM.png|700]]
the FM revolution caused many of CL problems were somewhat solved through scaling.

#### CL methods: 
- Plasticity: changing the model size and architecture size: even changing number of neurons
- Experience Replay
- Supervised Learning. Train on new datasets and evaluate on all previous datasets and new datasets. 
![[Screenshot 2025-02-20 at 3.56.09 PM.png|400]]
- Multi task learning: Simultaneously learn a model that does well jointly on all of them.
![[Screenshot 2025-02-20 at 3.58.21 PM.png|400]]
- Transfer Learning:
![[Screenshot 2025-02-20 at 3.59.59 PM.png|400]]
- Meta Learning
FMs took over Meta Learning: [[Language models are few shot learner.pdf]]

#### Continual Learning Settings: (X=input, Y=label , T=task)
- Task ID known at training:
	- T observed at test: task-incremental CL
	- T not observed at test: Class incremental or Domain Incremental CL
- Task ID not known at training:
	- task-agnostic

**Task-incremental:** Train on different supervised datasets. We know during training and testing which dataset we are on.
![[Screenshot 2025-02-20 at 4.18.03 PM.png|700]]
**Class-incremental**: **Add new Classes.** Similar, we know which task we are on during test and train, But the set of labels increases. 
![[Screenshot 2025-02-20 at 4.19.23 PM.png|700]]
**Task-agnostic CL : Most challenging**
We train on several tasks (we may notice distribution changes) but we don't know when it changes during training or testing.
![[Screenshot 2025-02-20 at 4.20.57 PM.png|700]]

Why CL is more challenging than SL?
In SL, all data is available so we can compute error and optimize for all data. 
If we have a sequential data, we cannot compute that objective unless we keep all data in memory (but that wouldn't be continual learning anymore!)

#### The Curse of Catastrophic Forgetting:

> The reason for catastrophic forgetting is "the very thing--a single set of shared weights-- that gave the networks their remarkable abilities to generalize and degrade gracefully." (French, 1999)

![[Screenshot 2025-02-20 at 5.26.35 PM.png|700]]


![[Screenshot 2025-02-20 at 5.30.46 PM.png|700]]

#Research_Idea: Do CL methods stand the test of scalability of models and data. Are they really necessary? Can we solve forgetting vs. adaptability by scaling up models and data. Are more sophisticated methods necessary? Need a systematic study. Many papers just present more sophisticated methods and compare with other methods on fixed size datasets.


#paper: [[brain foundation models.pdf]] uses eeg signals as a modality 
#paper: New Time series foundation model: [[chronos.pdf]]
#paper: Foundation models for probabilistic time series forecasting: [[laglama.pdf]]


#Research_Idea: The way we tokenize matters as well as model and quality of the model. The model is better if it can transfer knowledge to other modalities. transfer could be zero or even negative. Open research Question: What does it depend on? tokenizer, optimizer, pertaining data for model, and internal measurements. Good, bad and ugly side of transfer!? topic for many projects!

#book: Important book for time series analysis: [[A-Course-in-Time-Series-Analysis-Suhasini.pdf]]
#book: another book: [[Time Series Analysis and Its Applications Robert David.pdf]]

#paper: [[learning to learn without forgetting by maximizing transfer and minimizing interference.pdf]]
![[Screenshot 2025-02-21 at 12.14.38 PM.png|700]]

![[Screenshot 2025-02-21 at 12.17.59 PM.png]]

#paper: [[A continual learning survey- Defying forgetting in classification tasks.pdf]]

![[Screenshot 2025-02-21 at 12.25.02 PM.png]]

![[Screenshot 2025-02-21 at 12.25.14 PM.png]]

# The scale revolution happened!
![[Screenshot 2025-02-21 at 12.27.15 PM.png|]]

#paper: important: [[effect_of_scale_on_catastrophic_fortetting.pdf]]

![[Screenshot 2025-02-21 at 12.28.33 PM.png]]

#paper: [[simple and scalable strategies to continually pretrain large language models.pdf]]
![[Screenshot 2025-02-21 at 12.28.33 PM.png]]

