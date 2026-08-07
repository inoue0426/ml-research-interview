# ML Systems

Research Engineer 面接を意識して、モデルの数式だけでなく「実際にどう学習・推論するか」を説明できる状態を目指す。

## GPU / Compute

- [ ] GPU architecture basics
- [ ] CUDA execution model
- [ ] Compute vs memory bandwidth
- [ ] Kernel fusion

## Distributed Training

- [ ] Memory accounting
- [ ] Mixed precision
- [ ] Data parallelism
- [ ] Tensor parallelism
- [ ] Pipeline parallelism
- [ ] FSDP / ZeRO
- [ ] Activation checkpointing
- [ ] Communication collectives

## Inference

- [ ] KV cache
- [ ] Continuous batching
- [ ] Quantization
- [ ] Speculative decoding
- [ ] Throughput vs latency

## Core Systems Exercise

### 70B model memory estimation

考える項目:

1. parameters
2. gradients
3. optimizer states
4. activations
5. precision
6. sharding strategy
7. communication overhead
8. throughput bottleneck

面接では数値を暗記するのではなく、仮定を明示して概算できることを目標にする。
