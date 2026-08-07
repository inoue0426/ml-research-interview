# Minimum Knowledge — Research Reasoning

ここは知識暗記より、**曖昧な研究問題を hypothesis → experiment → interpretation に分解する力**を確認する。

## Problem Formulation
- [ ] research question と engineering objective を分ける
- [ ] measurable hypothesis に落とす
- [ ] baseline を選ぶ
- [ ] success metric を定義する

## Experimental Design
- [ ] controlled comparison
- [ ] ablation study
- [ ] hyperparameter fairness
- [ ] multiple seeds / variance
- [ ] train/validation/test leakage
- [ ] statistical vs practical significance

## Diagnosis
結果が悪いときに以下を分離する。
- [ ] data issue
- [ ] optimization issue
- [ ] architecture issue
- [ ] objective mismatch
- [ ] evaluation issue
- [ ] implementation bug
- [ ] insufficient compute / training

## Reading Results
- [ ] aggregate metric だけを見ない
- [ ] subgroup analysis
- [ ] failure cases
- [ ] calibration
- [ ] scaling behavior
- [ ] qualitative inspection の役割

## Causality of Improvements
- [ ] parameter count の増加と method contribution を分離
- [ ] extra data / compute の影響を分離
- [ ] leakage / contamination を疑う
- [ ] ablation で mechanism claim を検証

## Negative Results
- [ ] hypothesis が間違っていた場合
- [ ] experiment が inconclusive な場合
- [ ] measurement が弱い場合
- [ ] 次の最小コスト experiment を決める

## Open-ended Drills
1. 7B → 70B にしても validation loss がほぼ改善しない。何を調べる？
2. Training loss は下がるが downstream performance が悪化する。なぜ？
3. 新しい module で benchmark が +2% 改善した。本当に module の効果か？
4. ある dataset でだけ大きく改善する。何を疑う？
5. 再現実験で結果が出ない。どう切り分ける？
6. Compute budget が 10% しか残っていない。次の experiment は何にする？

## Answer Framework
1. Clarify objective / metric
2. List hypotheses
3. Rank by likelihood × impact × test cost
4. Design discriminating experiments
5. State expected outcomes
6. Identify confounders
7. Decide next action
