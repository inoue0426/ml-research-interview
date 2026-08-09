# PyTorch Interview Readiness

目的: GPT / 検索なしでも **面接中にコア実装で手が止まらないレベル**まで PyTorch の fluency を戻す。

API 暗記を目的にしない。重要なのは **tensor shape / autograd / model structure / masking / training flow を理解から再構成できること**。

## Level A — 参照なしで書けるようにする

- tensor creation / reshape / transpose / matmul
- broadcasting / indexing / masking
- `nn.Module` + `forward`
- simple MLP
- basic training loop
- `loss.backward()` / `optimizer.step()`
- softmax / cross entropy のコア
- scaled dot-product attention
- causal mask
- tensor shape reasoning

## Level B — 軽い API 参照で実装できればよい

- multi-head attention
- Transformer block
- Dataset / DataLoader
- custom loss / metric
- autoregressive decoding
- checkpoint save/load
- scheduler
- gradient clipping / accumulation

## Level C — 原理を理解し、API は調べてよい

- AMP / mixed precision
- DDP / FSDP
- distributed checkpointing
- profiling
- optimized attention / FlashAttention
- production KV cache / serving

## Files

1. `01_tensor_fluency.md`
2. `02_autograd_training_loop.md`
3. `03_nn_module_mlp.md`
4. `04_data_pipeline.md`
5. `05_attention_masking.md`
6. `06_transformer_block.md`
7. `07_decoding_kv_cache.md`
8. `08_debugging.md`
9. `09_training_utilities.md`
10. `10_distributed_amp.md`
11. `practice_checklist.md`

## Readiness criterion

各 Level A 項目について:

- [ ] 何も見ずに概念を説明できる
- [ ] 20–40 行程度なら参照なしで書ける
- [ ] tensor shape を追える
- [ ] time / memory complexity を説明できる
- [ ] よくある bug を見つけられる

Level B/C は API の完全暗記を求めない。
