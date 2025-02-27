Lecture on DeepSeek
***

- Paper pdf: [[DeepSeek-R1- Incentivizing Reasoning Capability in LLMs via Reinforcement Learning.pdf]]
- Paper link: [https://arxiv.org/abs/2501.12948](https://arxiv.org/abs/2501.12948)
- Powerpoint: [[DeepSeek-R1.pdf]]

Other Sources:
- Blog post:  [[Open-R1_ a fully open reproduction of DeepSeek-R1.pdf]]
- blog post:  [[DeepSeek-R1 explained _ Pioneering the Next Era of Reasoning-Driven AI.pdf]]

> [!PDF|255, 208, 0] [[DeepSeek-R1- Incentivizing Reasoning Capability in LLMs via Reinforcement Learning.pdf#page=5&annotation=669R|DeepSeek-R1- Incentivizing Reasoning Capability in LLMs via Reinforcement Learning, p.5]]
> > Previous work has heavily relied on large amounts of supervised data to enhance model performance. In this study, we demonstrate that reasoning capabilities can be significantly improved through large-scale reinforcement learning (RL), even without using supervised fine-tuning (SFT) as a cold start.   Furthermore, performance can be further enhanced with the inclusion of a small amount of cold-start data.


> [!PDF|67, 122, 0] [[DeepSeek-R1- Incentivizing Reasoning Capability in LLMs via Reinforcement Learning.pdf#page=8&annotation=694R|DeepSeek-R1- Incentivizing Reasoning Capability in LLMs via Reinforcement Learning, p.8]]
> > One of the most remarkable aspects of this self-evolution is the emergence of sophisticated behaviors as the test-time computation increases. Behaviors such as reflection—where the model revisits and reevaluates its previous steps—and the exploration of alternative approaches to problem-solving arise spontaneously. These behaviors are not explicitly programmed but instead emerge as a result of the model’s interaction with the reinforcement learning environment. This spontaneous development significantly enhances DeepSeek-R1-Zero’s reasoning capabilities, enabling it to tackle more challenging tasks with greater efficiency and accuracy.

> [!PDF|67, 122, 0] [[DeepSeek-R1- Incentivizing Reasoning Capability in LLMs via Reinforcement Learning.pdf#page=15&annotation=738R|DeepSeek-R1- Incentivizing Reasoning Capability in LLMs via Reinforcement Learning, p.15]]
> > Therefore, we can draw two conclusions: First, distilling more powerful models into smaller ones yields excellent results, whereas smaller models relying on the large-scale RL mentioned in this paper require enormous computational power and may not even achieve the performance of distillation. Second, while distillation strategies are both economical and effective, advancing beyond the boundaries of intelligence may still require more powerful base models and largerscale reinforcement learning.

### GRPO:
![[Screenshot 2025-02-25 at 2.43.03 PM.png]]

### Steps taken in improving DeepSeek-R1-zero and creating DeepSeek-R1:

![[Screenshot 2025-02-25 at 2.50.45 PM.png|600]]

![[Screenshot 2025-02-25 at 2.48.53 PM.png]]
![[Screenshot 2025-02-25 at 2.51.22 PM.png|400]]
![[Screenshot 2025-02-25 at 2.51.39 PM.png]]
![[Screenshot 2025-02-25 at 3.04.39 PM.png|220]]

> [!PDF|crucial] [[DeepSeek-R1- Incentivizing Reasoning Capability in LLMs via Reinforcement Learning.pdf#page=15&selection=63,0,68,29&color=crucial|DeepSeek-R1- Incentivizing Reasoning Capability in LLMs via Reinforcement Learning, p.15]]
> > Therefore, we can draw two conclusions: First, distilling more powerful models into smaller ones yields excellent results, whereas smaller models relying on the large-scale RL mentioned in this paper require enormous computational power and may not even achieve the performance of distillation. Second, while distillation strategies are both economical and effective, **advancing beyond the boundaries of intelligence may still require more powerful base models and larger-scale reinforcement learning.**
> 
