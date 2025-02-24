This lecture contains two paper presentations.
***
## Paper 1: Representation Projection Invariance Mitigates Representation Collapse

Link: [https://arxiv.org/abs/2205.11603](https://arxiv.org/abs/2205.11603)
paper pdf: [[Representation Projection Invariance Mitigates Representation Collapse.pdf]]

![[Representation Projection Invariance Mitigates Representation Collapse.pdf#page=2&rect=318,330,511,391|Representation Projection Invariance Mitigates Representation Collapse, p.2|400]]

> [!PDF|255, 208, 0] [[Representation Projection Invariance Mitigates Representation Collapse.pdf#page=2&annotation=1136R|Representation Projection Invariance Mitigates Representation Collapse, p.2]]
> The intuition behind the regularization objective is to incentivize the representations to be invariant under some projection ϕ ∈ Φ; pre-trained representations can be constructed from the fine-tuned representations by applying a function ϕ ∈ Φ.

> [!PDF|] [[Representation Projection Invariance Mitigates Representation Collapse.pdf#page=4&selection=26,13,46,38|Representation Projection Invariance Mitigates Representation Collapse, p.4]]
> > In contrast to catastrophic forgetting, we measure representation collapse as the loss in expressive power of the representations irrespective of the performance on pre-training task. A method known to alleviate catastrophic forgetting is Weight Consolidation (Chen et al., 2020; Kirkpatrick et al., 2017). It regularizes the fine-tuning process by encouraging fine-tuned weights to be close to the pre-trained weights. In contrast to weight consolidation, REPINA does not put direct constraints on weight updates, but rather tries to control the structural changes in representations.

> [!PDF|67, 122, 0] [[Representation Projection Invariance Mitigates Representation Collapse.pdf#page=6&annotation=1165R|Representation Projection Invariance Mitigates Representation Collapse, p.6]]
> our methods demonstrate higher stability and less fraction of failed runs than other approaches.

![[Representation Projection Invariance Mitigates Representation Collapse.pdf#page=5&rect=64,670,528,776&color=yellow|Representation Projection Invariance Mitigates Representation Collapse, p.5]]
![[Representation Projection Invariance Mitigates Representation Collapse.pdf#page=6&rect=314,486,509,592&color=yellow|Representation Projection Invariance Mitigates Representation Collapse, p.6|400]]

![[Representation Projection Invariance Mitigates Representation Collapse.pdf#page=8&rect=305,364,531,542&color=yellow|Representation Projection Invariance Mitigates Representation Collapse, p.8|400]]


Question: Q1. In the paper, it seems like they only target language models and NLP. Do you think their regularization method Repina could be useful in tasks outside of NLP, like for vision models or multi-modal foundation models? (where representation quality is also really crucial) or even in Reinforcement learning. It seems to me that some mention of other modalities should have been a part of this paper since NLP is not the only application of this regularization methods. Do you think any challenges could arise if we apply this method to domains outside of NLP?
## Paper 2: Open X-Embodiment: Robotic Learning Datasets and RT-X Models
Link: [https://arxiv.org/abs/2310.08864](https://arxiv.org/abs/2310.08864)
Paper pdf: [[Open-Embodiment- Robotic Learning Datasets and RT-XModels.pdf]]
Paper website: [https://robotics-transformer-x.github.io/](https://robotics-transformer-x.github.io/)

> [!PDF|255, 208, 0] [[Open-Embodiment- Robotic Learning Datasets and RT-XModels.pdf#page=3&annotation=691R|Open-Embodiment- Robotic Learning Datasets and RT-XModels, p.3]]
> We introduce the Open X-Embodiment Repository (robotics-transformer-x.github.io) – an open-source repository which includes large-scale data along with pre-trained model checkpoints for X-embodied robot learning research.

> [!PDF|] [[Open-Embodiment- Robotic Learning Datasets and RT-XModels.pdf#page=1&selection=687,1,700,60|Open-Embodiment- Robotic Learning Datasets and RT-XModels, p.1]]
> Conventionally, robotic learning methods train a separate model for every application, every robot, and even every environment. Can we instead train “generalist” X-robot policy that can be adapted efficiently to new robots, tasks, and environments? In this paper, we provide datasets in standardized data formats and models to make it possible to explore this possibility in the context of robotic manipulation, alongside experimental results that provide an example of effective X-robot policies. We assemble a dataset from 22 different robots collected through a collaboration between 21 institutions, demonstrating 527 skills (160266 tasks). We show that a high-capacity model trained on this data, which we call RT-X, exhibits positive transfer and improves the capabilities of multiple robots by leveraging experience from other platforms.



