# Minimum Knowledge — ML Systems

Research Engineer を想定し、モデルの数式だけでなく**どこに memory / compute / communication cost が出るか**を説明できるようにする。

## Hardware Basics
- [ ] CPU vs GPU
- [ ] GPU の massive parallelism
- [ ] HBM / memory bandwidth
- [ ] compute-bound vs memory-bound
- [ ] FLOPs と bandwidth の違い
- [ ] kernel launch の概念

## Numerical Precision
- [ ] FP32 / FP16 / BF16
- [ ] mixed precision training
- [ ] loss scaling の概念
- [ ] quantization: INT8 / lower precision の基本

## Training Memory
- [ ] parameters
- [ ] gradients
- [ ] optimizer states
- [ ] activations
- [ ] activation checkpointing
- [ ] optimizer memory が大きくなる理由

## Distributed Training
- [ ] data parallelism
- [ ] all-reduce
- [ ] DDP
- [ ] ZeRO / FSDP の目的
- [ ] tensor parallelism
- [ ] pipeline parallelism
- [ ] communication overhead
- [ ] strong scaling / weak scaling の直感

## Training Performance
- [ ] batch size
- [ ] gradient accumulation
- [ ] throughput
- [ ] utilization
- [ ] data-loader bottleneck
- [ ] checkpointing / fault tolerance

## LLM Inference
- [ ] prefill vs decode
- [ ] KV cache memory
- [ ] dynamic / continuous batching の概念
- [ ] latency vs throughput
- [ ] memory bandwidth bottleneck
- [ ] quantization
- [ ] speculative decoding
- [ ] tensor parallel inference

## Memory Estimation Exercise
70B parameter model について以下を概算できること。
- [ ] FP16/BF16 parameter memory
- [ ] gradient memory
- [ ] Adam optimizer states
- [ ] activation memory が何に依存するか
- [ ] 8 × 80 GB GPU で単純に載るか
- [ ] FSDP / TP / PP をどう使うか

## Debugging
- [ ] OOM の切り分け
- [ ] low GPU utilization
- [ ] communication bottleneck
- [ ] data pipeline bottleneck
- [ ] NaN / overflow
- [ ] reproducibility

## Must-answer Questions
1. What is the memory footprint of training a 70B model?
2. Data parallelism vs tensor parallelism?
3. Why does FSDP reduce memory?
4. What is an all-reduce?
5. Why can inference become memory-bandwidth bound?
6. What is KV cache and why can it dominate serving memory?
7. How would you improve training throughput?
8. How would you diagnose GPUs sitting idle?
