# nn.Module & Simple Models

Priority: ★★★★★

## 参照なしで実装

- [ ] `nn.Module` subclass
- [ ] `__init__`
- [ ] `forward`
- [ ] `nn.Linear`
- [ ] ReLU / GELU
- [ ] dropout の基本
- [ ] simple MLP classifier / regressor
- [ ] parameter inspection

## Minimum implementation target

以下を 10–15 分で書けること。

```text
input -> Linear -> activation -> Linear -> output
```

## Must explain

1. `__init__` と `forward` の役割。
2. `nn.Parameter` は何か。
3. model parameters は autograd とどう接続されるか。
4. output dimension を task に応じてどう決めるか。
5. classification で logits に softmax を明示的にかけない場合があるのはなぜか。

## Optional

- [ ] LayerNorm を使う小モデル
- [ ] residual MLP block
- [ ] embedding layer
