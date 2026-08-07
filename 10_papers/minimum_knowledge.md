# Minimum Knowledge — Papers

大量の paper summary を作るのではなく、**現在の ML / frontier model research を理解するための canonical ideas** を説明できる状態にする。

## Transformer / Language Models
最低限、以下の contribution を説明できること。
- [ ] Attention Is All You Need — Transformer / self-attention
- [ ] BERT — masked language modeling / encoder pretraining
- [ ] GPT-style autoregressive pretraining — decoder-only scaling
- [ ] scaling laws — parameters / data / compute
- [ ] Chinchilla — compute-optimal data/model tradeoff

## Post-training / RL
- [ ] policy gradient / PPO の代表的考え方
- [ ] InstructGPT — SFT + reward model + RLHF
- [ ] DPO — direct preference optimization

## Representation Learning
- [ ] contrastive learning の canonical formulation
- [ ] masked modeling
- [ ] self-supervised learning の基本思想

## Generative Models
- [ ] VAE
- [ ] GAN
- [ ] diffusion models

## AI for Science
自分の専門領域では、少なくとも以下を説明できる代表論文を選ぶ。
- [ ] protein sequence / structure foundation model
- [ ] molecular generative / representation model
- [ ] single-cell foundation model
- [ ] multimodal biological model
- [ ] scientific agent / reasoning system

## Paper Reading Template
1. What problem is being solved?
2. Why were previous approaches insufficient?
3. What is the one-sentence key idea?
4. What is technically new?
5. What experiment actually supports the claim?
6. Which ablation matters most?
7. What is the weakest assumption?
8. What would I try next?

## Rule
Paper title・年号・細かい benchmark score の暗記より、**idea / mechanism / evidence / limitation** を優先する。
