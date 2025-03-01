This class contains two paper presentations
***

## Paper 1: Investigating Continual Pretraining in Large Language Models: Insights and Implications

Paper pdf: [[Investigating Continual Pretraining in Large Language Models Insights and Implications.pdf]]
Paper link: https://arxiv.org/abs/2402.17400

> [!PDF|255, 208, 0] [[Investigating Continual Pretraining in Large Language Models Insights and Implications.pdf#page=1&annotation=1163R|Investigating Continual Pretraining in Large Language Models Insights and Implications, p.1]]
> Our primary emphasis is on  continual domain-adaptive pretraining, a process designed to equip LLMs with the ability to integrate new information from various domains while retaining previously learned knowledge. We further examine the impact of model size on learning efficacy and forgetting, as well as how the progression and similarity of emerging domains affect the knowledge transfer within these models.

> [!PDF|] [[Investigating Continual Pretraining in Large Language Models Insights and Implications.pdf#page=1&selection=44,43,59,28|Investigating Continual Pretraining in Large Language Models Insights and Implications, p.1]]
> 1.  continual pretraining consistently improves < 1.5B models studied in this work and is also superior to domain adaptation
> 
> 1.  larger models always achieve better perplexity than smaller ones when continually pretrained on the same corpus
> 
> 1.  smaller models are particularly sensitive to continual pretraining, showing the most significant rates of both learning and forgetting
> 
> 1.  continual pretraining boosts downstream task performance of GPT-2 family
> 
> 1.  continual pretraining enables LLMs to specialize better when the sequence of domains shows semantic similarity while randomizing training domains leads to better transfer and final performance otherwise.

> [!PDF|255, 208, 0] [[Investigating Continual Pretraining in Large Language Models Insights and Implications.pdf#page=2&annotation=1208R|Investigating Continual Pretraining in Large Language Models Insights and Implications, p.2]]
> Continual learning works in LLMs can broadly be divided into two sub-categories:
> 
> - Continual fine-tuning:** incrementally fine-tunes an LLM on a sequence of downstream tasks
> - **Continual domain-adaptive pretraining:**  adapting LLMs to new domains through incremental updates, thereby avoiding the need for exhaustive retraining whenever new data becomes available.

