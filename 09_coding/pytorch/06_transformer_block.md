# Transformer Block

Priority: ★★★★★

## 軽い参照で実装できればよい

- [ ] embedding
- [ ] positional information / RoPE の位置づけ
- [ ] LayerNorm / RMSNorm
- [ ] multi-head self-attention
- [ ] residual connection
- [ ] MLP / FFN
- [ ] Pre-LN block
- [ ] output projection

## Whiteboard target

```text
x
├─ norm -> self-attention -> + residual
└─ norm -> MLP            -> + residual
```

## Shape reasoning

```text
[B,T,D]
  -> Q/K/V [B,H,T,Dh]
  -> attention [B,H,T,Dh]
  -> merge [B,T,D]
  -> MLP [B,T,Dff] -> [B,T,D]
```

## Must explain

1. attention と MLP の役割の違い。
2. residual connection が必要な理由。
3. Pre-LN vs Post-LN。
4. decoder-only Transformer で causal masking が必要な理由。
5. parameter count が主に何で決まるか。

## Implementation target

完全な GPT を暗記実装する必要はない。`Attention` と `MLP` を組み合わせた 1 block を、API を少し確認すれば書けること。
