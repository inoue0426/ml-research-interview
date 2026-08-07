# Transformers & LLMs

この領域は重点補強。

## Topics

- [ ] Attention
- [ ] Transformer architecture
- [ ] Positional encoding / RoPE
- [ ] Tokenization
- [ ] Language modeling objective
- [ ] Pretraining
- [ ] Scaling laws
- [ ] Training data
- [ ] Instruction tuning
- [ ] Reward modeling
- [ ] RLHF
- [ ] DPO and preference optimization
- [ ] Reasoning
- [ ] Agents / tool use
- [ ] Inference
- [ ] KV cache
- [ ] Long context
- [ ] Evaluation
- [ ] Interpretability

## 学習時の確認軸

各トピックについて、最低限以下を説明できる状態を目標にする。

1. 何を解決する手法か
2. 数式・アルゴリズム
3. intuition
4. computational / memory complexity
5. implementation
6. failure modes
7. alternatives / trade-offs
8. 30秒での英語説明
9. follow-up question への回答

## Core Interview Questions

- Why does scaled dot-product attention divide by `sqrt(d_k)`?
- Why use multiple attention heads?
- What is the computational complexity of self-attention?
- Pre-LN vs Post-LN?
- What exactly is stored in the KV cache?
- MHA vs MQA vs GQA?
- What changes between pretraining and post-training?
- Why can scaling improve model capability?
- What are the bottlenecks in long-context inference?
- How would you evaluate a reasoning model?
