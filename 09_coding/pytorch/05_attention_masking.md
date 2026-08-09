# Attention & Masking

Priority: ★★★★★

## 参照なしで再構成できるようにする

- [ ] Q / K / V projection の意味
- [ ] scaled dot-product attention
- [ ] `Q @ K.transpose(-2, -1)`
- [ ] `sqrt(d_k)` scaling
- [ ] softmax の dimension
- [ ] causal mask
- [ ] padding mask の概念
- [ ] attention dropout の位置
- [ ] output = weights @ V

## Core equation

\[
\mathrm{Attention}(Q,K,V)
= \mathrm{softmax}\left(\frac{QK^\top}{\sqrt{d_k}} + M\right)V
\]

## Shape target

```text
Q,K,V:   [B, H, T, Dh]
scores:  [B, H, T, T]
weights: [B, H, T, T]
out:     [B, H, T, Dh]
```

## Must implement

- [ ] single-head scaled dot-product attention
- [ ] causal masking
- [ ] multi-head split / merge の核心

## Must explain

1. なぜ `sqrt(d_k)` で割るか。
2. mask は softmax の前か後か、なぜか。
3. causal mask と padding mask の違い。
4. sequence length が 2 倍になると何が増えるか。
5. MHA / MQA / GQA の違いは何か。

## 暗記不要

- optimized attention API の正確な signature
- FlashAttention kernel implementation
