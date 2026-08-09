# Distributed Training & AMP

Priority: ★★☆☆☆

## 原理を理解、API は調べてよい

- [ ] mixed precision の目的
- [ ] FP16 / BF16 の違いの基本
- [ ] autocast の概念
- [ ] loss scaling の概念
- [ ] data parallelism
- [ ] DDP の基本
- [ ] gradient all-reduce
- [ ] FSDP / ZeRO の目的
- [ ] tensor parallelism / pipeline parallelism との違い

## Must explain

1. mixed precision で何が速く / 軽くなるか。
2. FP16 で loss scaling が必要になることがある理由。
3. DDP では各 GPU が何を持ち、gradient をどう同期するか。
4. FSDP が memory を減らす理由。
5. communication が bottleneck になるのはいつか。

## 暗記不要

- process group 初期化コード
- launcher の exact syntax
- FSDP configuration options
- NCCL 関連 API

面接では API 記憶より systems reasoning を優先する。
