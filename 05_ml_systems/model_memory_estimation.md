# Model Memory Estimation

Status: 🔴
Priority: ★★★★★

## 最低限押さえる
70B parameter model を例に、概算できること。

- [ ] BF16/FP16 parameters
- [ ] gradients
- [ ] Adam first/second moments
- [ ] master weights を持つ場合
- [ ] activations が batch / sequence / hidden size / layers に依存すること
- [ ] 8 × 80GB GPU に単純配置できるか
- [ ] FSDP / TP / PP のどれを使うか

## 日本語で理解

## English Explanation

## Exercises
1. 70B × 2 bytes = ?
2. Training states を含めると何倍程度になるか？前提を明示する。
3. Inference と training で memory profile はどう違う？
4. Context length を2倍にしたら何が増える？

## Interview Answer — 2 min

## Personal Notes / TODO
