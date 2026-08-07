# Minimum Knowledge — Deep Learning

## Neural Network Fundamentals
- [ ] affine layer + nonlinearity
- [ ] universal approximation の意味と限界
- [ ] forward pass / computational graph
- [ ] backpropagation / chain rule
- [ ] vanishing / exploding gradients

## Activations
- [ ] sigmoid / tanh / ReLU
- [ ] GELU / SiLU の直感
- [ ] saturation が gradient に与える影響

## Initialization & Normalization
- [ ] Xavier / He initialization
- [ ] BatchNorm
- [ ] LayerNorm
- [ ] RMSNorm
- [ ] BatchNorm と LayerNorm の違い
- [ ] Pre-LN vs Post-LN の基本

## Optimization & Regularization
- [ ] SGD / momentum / Adam / AdamW
- [ ] weight decay と L2 penalty の関係
- [ ] dropout
- [ ] early stopping
- [ ] learning-rate warmup / decay
- [ ] gradient clipping

## Architectures
- [ ] CNN: convolution, receptive field, weight sharing
- [ ] RNN / LSTM の基本と限界
- [ ] GNN / message passing
- [ ] Transformer へ移行する理由

## Representation Learning
- [ ] embedding
- [ ] metric learning
- [ ] contrastive learning
- [ ] self-supervised learning
- [ ] pretraining / fine-tuning

## Generative Modeling
- [ ] autoregressive models
- [ ] VAE: ELBO の意味
- [ ] GAN の基本
- [ ] diffusion model の forward / reverse process の直感

## GNN — 専門領域として defend できること
- [ ] message-passing formulation
- [ ] permutation invariance / equivariance
- [ ] expressivity と Weisfeiler–Lehman test
- [ ] oversmoothing
- [ ] oversquashing
- [ ] heterophily
- [ ] graph construction noise
- [ ] scalability
- [ ] GNN vs Transformer
- [ ] When NOT to use a GNN

## Must-answer Questions
1. Derive backpropagation for a simple MLP.
2. Why do deep networks need careful initialization?
3. BatchNorm vs LayerNorm — when and why?
4. Why can residual connections help optimization?
5. Why AdamW rather than Adam + naive L2?
6. What inductive bias does a GNN provide?
7. How would you determine whether a graph actually helps?
