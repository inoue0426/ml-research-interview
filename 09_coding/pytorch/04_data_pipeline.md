# Dataset, DataLoader & Batching

Priority: ★★★☆☆

## 軽い参照で実装できればよい

- [ ] custom `Dataset`
- [ ] `__len__` / `__getitem__`
- [ ] `DataLoader`
- [ ] batching
- [ ] shuffling
- [ ] padding / variable-length sequences
- [ ] custom `collate_fn` の概念
- [ ] train/validation split

## Must explain

1. Dataset と DataLoader の責務の違い。
2. batch dimension はどこで追加されるか。
3. variable-length sequence をどう batch 化するか。
4. data pipeline が GPU utilization を下げるケース。

## 暗記不要

- worker 関連の細かい引数
- pin-memory 等の正確な API
- distributed sampler の完全な書式

概念と debugging 方針を理解していればよい。
