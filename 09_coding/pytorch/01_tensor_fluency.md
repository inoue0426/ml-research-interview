# Tensor Fluency

Priority: ★★★★★

## 参照なしでできるようにする

- [ ] tensor creation: `tensor`, `zeros`, `ones`, `arange`
- [ ] `shape`, `size`, `dim`
- [ ] `reshape` / `view`
- [ ] `transpose` / `permute`
- [ ] `unsqueeze` / `squeeze`
- [ ] concatenation / stacking
- [ ] matrix multiplication: `@`, `matmul`
- [ ] broadcasting
- [ ] boolean masking
- [ ] slicing / advanced indexing
- [ ] reductions: `sum`, `mean`, `max`
- [ ] `softmax` dimension reasoning
- [ ] device / dtype basics

## Shape drills

以下を即答できること。

```text
X: [B, T, D]
W: [D, H]
X @ W -> [B, T, H]
```

```text
Q: [B, H, T, Dh]
K: [B, H, T, Dh]
Q @ K^T -> [B, H, T, T]
```

## Must explain

1. `reshape` と `transpose` は何が違うか。
2. broadcasting はいつ便利で、どんな silent bug を生むか。
3. softmax の `dim` を間違えると何が起きるか。
4. batch / sequence / feature / head dimension をどう追うか。

## Practice

- [ ] NumPy の式を PyTorch tensor operations に書き換える
- [ ] for-loop を vectorized operation にする
- [ ] attention の shape を紙で追ってからコードで確認する
