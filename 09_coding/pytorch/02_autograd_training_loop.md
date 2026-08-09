# Autograd & Training Loop

Priority: ★★★★★

## 参照なしで説明・実装

- [ ] forward pass
- [ ] loss computation
- [ ] `optimizer.zero_grad()`
- [ ] `loss.backward()`
- [ ] `optimizer.step()`
- [ ] gradient accumulation の意味
- [ ] `torch.no_grad()`
- [ ] `model.train()` vs `model.eval()`
- [ ] `requires_grad`
- [ ] computational graph の基本

## 最低限の training loop

```python
for x, y in loader:
    optimizer.zero_grad()
    pred = model(x)
    loss = criterion(pred, y)
    loss.backward()
    optimizer.step()
```

この形を暗記するのではなく、**各行が何をしているか説明できること**。

## Must explain

1. なぜ gradient を zero にするのか。
2. `backward()` は何を計算するのか。
3. `train()` / `eval()` は何に影響するか。
4. `no_grad()` と `detach()` の違い。
5. gradient accumulation を使う理由。

## Debugging drills

- [ ] gradient が `None` の原因を調べる
- [ ] accidental `detach()` を見つける
- [ ] NaN loss を切り分ける
- [ ] train/eval mode bug を見つける
