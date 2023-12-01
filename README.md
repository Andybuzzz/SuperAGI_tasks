# SuperAGI_tasks
# Task 1 
GPT2-small model (with 125 million parameters) model has downloaded form hugging face .
It has code for implementation of Multi-Head Self Attention (MHA), The Feed-forward module and the LayerNorm layer as per the original GPT2 architecture proposed in the paper. Andrei Karpathy's nanogpt repository helped me as the major reference in implementation

# TASK 2 
Providinf following teaks in model 
- **Rotary Positional Embedding:** Replace the original positional embeddings in the GPT-2 model with Rotary embeddings. You may refer to [Su et. al. RoFormer](https://arxiv.org/pdf/2104.09864.pdf).
- **Group Query Attention:** Equip your model with the Group Query Attention mechanism following the insights from the [Ainslie et. al. GQA: Training Generalized Multi-Query Transformer](https://arxiv.org/pdf/2305.13245v2.pdf). Analyze how this mechanism can modify the model's operation compared to the standard attention mechanism.
- **Sliding Window Attention:** Imbibe the Sliding Window Attention mechanism in your model and observe its effects on model performance. Refer to the work by [Beltagy et. al. Longformer](https://arxiv.org/pdf/2004.05150v2.pdf) for better comprehension of its implementation and advantages.

# TASK 3 Training Loop Implementatio
Creating a training loop considering given requirements in task
