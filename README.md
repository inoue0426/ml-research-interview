# ML Research Interview Prep

DeepMind / Anthropic などの frontier AI lab の Research Scientist / Research Engineer 面接に向けた学習・復習ノート。

このリポジトリは、ML を一から学び直すための教科書ではなく、既存の研究経験をベースに、面接で必要になる知識・説明力・研究 reasoning・実装力を整理するための knowledge base として使う。

## 基本方針

- **理解はまず日本語で整理する。** 英語を書くこと自体を学習のボトルネックにしない。
- 重要な内容には **English Explanation** を追加する。
- 面接で頻出・重要な内容には **30-second / 2-minute interview answer** を追加する。
- 英訳は直訳ではなく、実際の technical interview で自然に使える表現を優先する。
- 自分が既に強い領域は圧縮し、frontier model / RL / ML systems / coding を重点的に補強する。
- 各分野の知識は最終的に `11_interview_questions/` に interview-ready な形で収束させる。

## Positioning

既存の強み:

- AI for drug discovery / computational biology
- representation learning
- graph neural networks / heterogeneous graphs
- pharmacogenomics / drug response prediction
- single-cell ML
- protein representation learning
- interpretable biomedical ML
- research design / scientific reasoning

重点的に補強する領域:

- Transformer fundamentals
- LLM pretraining / post-training
- reinforcement learning
- ML systems / distributed training / inference
- general coding interviews
- frontier-model research reasoning

## Repository Structure

```text
ml-research-interview/
├── README.md
├── 00_interview_dashboard/
├── 01_ml_foundations/
├── 02_deep_learning/
├── 03_transformers_llms/
├── 04_reinforcement_learning/
├── 05_ml_systems/
├── 06_research_reasoning/
├── 07_ai_for_science/
├── 08_my_research/
├── 09_coding/
├── 10_papers/
├── 11_interview_questions/
├── cheatsheets/
└── templates/
```

## Priority

| Area | Priority | 方針 |
|---|---:|---|
| Transformer fundamentals | ★★★★★ | 深く理解 + 実装 + 面接回答 |
| LLM pre/post-training | ★★★★★ | 重点補強 |
| Reinforcement learning | ★★★★★ | 重点補強 |
| ML systems | ★★★★★ | 重点補強 |
| Coding | ★★★★★ | 独立して練習 |
| AI for Science | ★★★★★ | 差別化領域として整理 |
| My research / research defense | ★★★★★ | 面接用に変換 |
| Research reasoning | ★★★★☆ | 強みを interview format に変換 |
| Math / ML foundations | ★★★☆☆ | 復習中心 |
| GNN / representation learning | ★★☆☆☆ | 既存知識の圧縮・defense 中心 |
| Classical ML | ★★☆☆☆ | 面接 coverage 程度 |

## Standard Note Format

各ノートは必要に応じて以下の形式を使う。

```markdown
# Topic

## 日本語で理解

## English Explanation

## Key Vocabulary

## 数式 / Derivation

## Implementation

## Failure Modes / Limitations

## Interview Answer — 30 sec

## Interview Answer — 2 min

## Follow-up Questions

## Personal Notes / TODO
```

日本語部分は理解速度を優先して自由に書く。英語部分は、後から面接でそのまま使える簡潔で自然な technical English に整える。

## Learning Loop

```text
日本語で理解
    ↓
数式・実装で確認
    ↓
English explanation を追加
    ↓
30 sec / 2 min で説明
    ↓
follow-up questions に答える
    ↓
11_interview_questions/ に収束
```

## Current Goal

まずは次を優先して埋める。

1. Transformer / attention
2. LLM training and post-training
3. RL fundamentals → PPO / LLM RL
4. ML systems fundamentals
5. 自分の主要研究を interview defense 形式に変換
6. AI for Science の研究テーマを frontier-model 文脈で整理
