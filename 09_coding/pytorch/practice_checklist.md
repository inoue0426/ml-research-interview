# PyTorch Practice Checklist

この checklist は「API を暗記したか」ではなく、**面接でコア部分を自力で再構成できるか**を確認する。

## Tier 1 — Must write without reference

- [ ] tensor reshape / transpose / matmul を使った shape 操作
- [ ] simple `nn.Module`
- [ ] 2-layer MLP
- [ ] basic training loop
- [ ] softmax の正しい dimension
- [ ] boolean / causal masking
- [ ] scaled dot-product attention
- [ ] attention tensor shapes を説明
- [ ] simple loss + backward + optimizer step

## Tier 2 — Can use light reference

- [ ] multi-head attention
- [ ] Transformer block
- [ ] custom Dataset / DataLoader
- [ ] autoregressive generation loop
- [ ] gradient clipping
- [ ] gradient accumulation
- [ ] checkpoint save/load

## Tier 3 — Understand conceptually

- [ ] AMP
- [ ] DDP
- [ ] FSDP
- [ ] optimized attention
- [ ] production KV cache
- [ ] distributed checkpointing

## Timed drills

### 10 min
- [ ] MLP + forward
- [ ] training loop
- [ ] tensor shape exercise

### 15 min
- [ ] scaled dot-product attention + causal mask
- [ ] simple Dataset + DataLoader usage

### 25–30 min
- [ ] multi-head attention
- [ ] one Pre-LN Transformer block

## Debugging drills

- [ ] wrong attention mask
- [ ] wrong softmax dimension
- [ ] detached gradient
- [ ] wrong train/eval mode
- [ ] accidental broadcasting
- [ ] device mismatch
- [ ] NaN loss

## Done criteria

PyTorch fluency が戻ったとみなす基準:

1. 30–50 行程度のコア PyTorch を GPT / 検索なしで書ける。
2. API を忘れても pseudocode と tensor shapes は止まらない。
3. Attention / MLP / training loop の bug を自分で切り分けられる。
4. Transformer 全体を暗記実装する必要はなく、各 component を理解から組み立てられる。
