# PyTorch Debugging

Priority: ★★★★★

## 必須

- [ ] tensor shape mismatch
- [ ] wrong softmax dimension
- [ ] accidental broadcasting
- [ ] CPU / GPU device mismatch
- [ ] dtype mismatch
- [ ] detached gradients
- [ ] in-place operation issues の基本
- [ ] NaN / inf loss
- [ ] exploding gradients
- [ ] train/eval mode bug
- [ ] padding / causal mask bug
- [ ] label / target shape mismatch

## Debugging routine

1. shape を print / assert する
2. dtype / device を確認する
3. loss が最初から有限か確認する
4. gradient norm を確認する
5. 小さい batch / toy data で overfit できるか確認する
6. masking / normalization / reduction dimension を確認する

## Must answer

1. Loss が下がらないとき何から確認するか。
2. Gradient が全部 zero / None のとき何を見るか。
3. Train は良いが eval が壊れる場合の候補は何か。
4. GPU memory が急増したとき何を疑うか。
5. Attention implementation の silent bug はどこに入りやすいか。
