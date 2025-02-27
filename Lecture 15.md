This lecture contains two papers.
***
## Paper 1: Simple and Scalable Strategies to Continually Pre-train Large Language Models

paper pdf: [[Simple and Scalable Strategies to Continually Pre-train Large Language Models.pdf]]
paper link: https://arxiv.org/abs/2403.08763

> [!PDF|67, 122, 0] [[Simple and Scalable Strategies to Continually Pre-train Large Language Models.pdf#page=1&annotation=2766R|Simple and Scalable Strategies to Continually Pre-train Large Language Models, p.1]]
> > In this work, we show that a simple and scalable combination of learning rate (LR) re-warming, LR re-decaying, and replay of previous data is sufficient to match the performance of fully re-training from scratch on all available data, as measured by the final loss and the average score on several language model (LM) evaluation benchmarks
> 

> [!PDF|255, 208, 0] [[Simple and Scalable Strategies to Continually Pre-train Large Language Models.pdf#page=1&annotation=2769R|Simple and Scalable Strategies to Continually Pre-train Large Language Models, p.1]]
> >  Specifically, we show this for a weak but realistic distribution shift between two commonly used LLM pre-training datasets (English→English) and a stronger distribution shift (English→German) at the 405M parameter model scale with large dataset sizes (hundreds of billions of tokens
> 

> [!PDF|255, 208, 0] [[Simple and Scalable Strategies to Continually Pre-train Large Language Models.pdf#page=2&annotation=2792R|Simple and Scalable Strategies to Continually Pre-train Large Language Models, p.2]]
> We consider models trained on the union of existing datasets as baselines whose performance we seek to match using a combination of continual learning strategies at scale.

> [!PDF|255, 208, 0] [[Simple and Scalable Strategies to Continually Pre-train Large Language Models.pdf#page=2&annotation=2827R|Simple and Scalable Strategies to Continually Pre-train Large Language Models, p.2]]
> Contributions: 
> 1. We establish the effect of learning rate re-warming and re-decaying for decoder-only transformer-based LLMs pre-trained using a cosine schedule, showing that re-warming and re-decaying is necessary for adaptation during continual pre-training.
> 2. We establish the effect of replaying previous data while keeping compute constant across two distribution shifts and many replay percentages. We find that, even when updating decoder-only transformer-based LLMs on hundreds of billions of new tokens, it is possible to significantly mitigate forgetting with an appropriate amount of replay.
> 3. We demonstrate, across two model sizes and distribution shifts, that a simple and scalable combination of LR re-warming, LR re-decaying, and compute-equivalent replay allows continually pre-trained decoder-only transformer-based LLMs to attain similar performance on average to models re-trained on the union of all data while using significantly less compute.
> 4. We propose infinite learning rate schedules (schedules allowing smooth transition across datasets) for the continual pre-training of LLMs as a promising way to circumvent optimization difficulties associated with learning rate re-warming.
> 

![[Simple and Scalable Strategies to Continually Pre-train Large Language Models.pdf#page=4&rect=59,281,548,629&color=yellow|Simple and Scalable Strategies to Continually Pre-train Large Language Models, p.4]]

