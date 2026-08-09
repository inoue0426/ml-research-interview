# Training Utilities

Priority: ★★★☆☆

## 軽い参照で実装できればよい

- [ ] gradient clipping
- [ ] gradient accumulation
- [ ] learning-rate scheduler
- [ ] warmup の概念
- [ ] checkpoint save / load
- [ ] early stopping の基本
- [ ] reproducibility / seeds の基本
- [ ] metric logging

## Must explain

1. gradient clipping は何を防ぐか。
2. gradient accumulation は effective batch size とどう関係するか。
3. warmup が Transformer training で使われる理由。
4. checkpoint に何を保存すべきか。
5. reproducibility が完全には保証しづらい理由。

## 暗記不要

API signature や scheduler 名を丸暗記しない。概念と使いどころを説明できればよい。
