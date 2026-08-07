# Attention

Status: 🔴
Priority: ★★★★★

## 最低限押さえる
- [ ] Q / K / V
- [ ] scaled dot-product attention
- [ ] なぜ `sqrt(d_k)` で割るか
- [ ] causal mask
- [ ] multi-head attention
- [ ] time / memory complexity
- [ ] MHA / MQA / GQA

## 日本語で理解

## English Explanation

## Key Vocabulary

## 数式 / Derivation
- [ ] `softmax(QK^T / sqrt(d_k))V`
- [ ] dot-product variance が `d_k` に比例する説明

## Implementation
- [ ] scaled dot-product attention from scratch
- [ ] multi-head attention from scratch

## Interview Answer — 30 sec

## Interview Answer — 2 min

## Follow-up Questions
1. Why scale by `sqrt(d_k)`?
2. Why multiple heads?
3. What happens when sequence length doubles?
4. MHA vs MQA vs GQA?

## Personal Notes / TODO
