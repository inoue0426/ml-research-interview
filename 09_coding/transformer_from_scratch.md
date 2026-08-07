# Transformer from Scratch

Status: 🔴
Priority: ★★★★★

## Must Implement
- [ ] scaled dot-product attention
- [ ] causal mask
- [ ] multi-head self-attention
- [ ] Transformer block
- [ ] decoder-only Transformer
- [ ] positional information / RoPE simplified implementation
- [ ] autoregressive generation loop
- [ ] simple KV cache

## Must Explain While Coding
- tensor shapes
- where masking is applied
- `sqrt(d_k)` scaling
- time / memory complexity
- train vs generation path

## Interview Questions
1. Implement attention without `nn.MultiheadAttention`.
2. Where would you insert LayerNorm and residuals?
3. How would you add KV caching?

## Personal Notes / TODO
