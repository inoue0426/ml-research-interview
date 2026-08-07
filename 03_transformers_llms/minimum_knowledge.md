# Minimum Knowledge — Transformers & LLMs

このカテゴリは最優先。最低限、**数式 → architecture → training → inference → failure mode** を一本につなげて説明できること。

## Attention
- [ ] Q, K, V の意味
- [ ] scaled dot-product attention
- [ ] なぜ `sqrt(d_k)` で割るか
- [ ] causal mask
- [ ] multi-head attention
- [ ] attention の time / memory complexity
- [ ] MHA / MQA / GQA

## Transformer Architecture
- [ ] embedding
- [ ] positional encoding / RoPE
- [ ] residual connection
- [ ] LayerNorm / RMSNorm
- [ ] MLP / FFN block
- [ ] Pre-LN vs Post-LN
- [ ] encoder-only / decoder-only / encoder-decoder

## Language Modeling
- [ ] autoregressive factorization
- [ ] next-token prediction objective
- [ ] teacher forcing
- [ ] perplexity
- [ ] tokenization: BPE / unigram / byte-level の基本

## Pretraining
- [ ] data collection / deduplication / filtering
- [ ] data mixture
- [ ] train-validation contamination
- [ ] compute / data / parameter tradeoffs
- [ ] scaling laws の基本的考え方
- [ ] Chinchilla-style compute-optimal training の直感

## Post-training
- [ ] supervised fine-tuning
- [ ] preference data
- [ ] reward modeling
- [ ] RLHF の pipeline
- [ ] PPO を LLM に使うとき何を最適化しているか
- [ ] DPO の目的と RLHF との違い
- [ ] KL regularization の役割

## Reasoning & Agents
- [ ] chain-of-thought の基本的概念
- [ ] test-time compute / sampling
- [ ] tool use
- [ ] agent loop: observe → reason → act → observe
- [ ] planning と error recovery
- [ ] agent evaluation の難しさ

## Inference
- [ ] autoregressive decoding
- [ ] greedy / temperature / top-k / top-p
- [ ] KV cache
- [ ] prefill vs decode
- [ ] batching
- [ ] latency vs throughput
- [ ] quantization の基本
- [ ] speculative decoding の直感

## Long Context
- [ ] attention の quadratic cost
- [ ] positional extrapolation
- [ ] retrieval vs long-context prompting
- [ ] lost-in-the-middle など context utilization の問題

## Evaluation
- [ ] perplexity と downstream capability の違い
- [ ] benchmark contamination
- [ ] pass@k
- [ ] human / model-based evaluation
- [ ] robustness / calibration
- [ ] capability vs safety evaluation

## Interpretability & Safety — minimum
- [ ] activation / representation probing
- [ ] attribution の限界
- [ ] mechanistic interpretability の目的
- [ ] hallucination
- [ ] jailbreak / prompt injection の基本
- [ ] reward hacking / specification gaming

## Must Implement
- [ ] scaled dot-product attention
- [ ] multi-head self-attention
- [ ] small decoder-only Transformer
- [ ] causal mask
- [ ] KV cache の簡易版

## Must-answer Questions
1. Why divide attention logits by `sqrt(d_k)`?
2. Why multiple attention heads?
3. What exactly is stored in the KV cache?
4. What happens computationally when context length doubles?
5. Why do decoder-only LMs work with next-token prediction?
6. Explain pretraining → SFT → preference optimization.
7. PPO vs DPO for LLM post-training.
8. What bottlenecks LLM inference?
9. How would you evaluate a new reasoning method?
10. What could make scaling stop helping?
