# Autoregressive Decoding & KV Cache

Priority: ★★★★☆

## 軽い参照で実装できればよい

- [ ] autoregressive token generation loop
- [ ] greedy decoding
- [ ] temperature sampling
- [ ] top-k / top-p の概念
- [ ] KV cache が何を保存するか
- [ ] prefill vs decode
- [ ] cached K/V を新しい token の K/V と concatenate する考え方

## Must explain

1. なぜ毎 step 過去 token の K/V を再計算しなくてよいか。
2. Q はなぜ新しい token について毎回必要か。
3. KV cache は compute と memory にどう影響するか。
4. MQA / GQA が KV cache memory を減らす理由。
5. prefill と decode で bottleneck がどう違うか。

## Implementation target

完全な production serving code は不要。小さい decoder-only model で、cache なし / ありの概念実装を追えること。

## 暗記不要

- paged attention の production 実装
- continuous batching API
- serving framework 固有 API
