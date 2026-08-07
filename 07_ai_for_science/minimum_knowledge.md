# Minimum Knowledge — AI for Science

この領域は差別化に使う。biology knowledge の羅列ではなく、**scientific ML 特有の modeling / evaluation / generalization 問題**として説明する。

## Scientific Data Characteristics
- [ ] small-n / high-dimensional data
- [ ] measurement noise
- [ ] batch effects
- [ ] missingness
- [ ] heterogeneous modalities
- [ ] weak / noisy labels
- [ ] dataset bias
- [ ] experimental confounding

## Biological Representations
- [ ] DNA / RNA sequence
- [ ] protein sequence / structure
- [ ] molecular graph / SMILES
- [ ] gene-expression vector
- [ ] cell / tissue representation
- [ ] biological knowledge graph

各 modality について、なぜその representation を使うか説明する。

## Modeling Choices
- [ ] sequence model
- [ ] GNN
- [ ] Transformer
- [ ] multimodal model
- [ ] contrastive learning
- [ ] generative modeling
- [ ] retrieval / knowledge augmentation

## Foundation Models for Biology
- [ ] pretraining objective
- [ ] tokenization / representation choice
- [ ] scaling data availability
- [ ] transfer learning
- [ ] zero-shot / few-shot evaluation
- [ ] biological validity vs benchmark performance

## Scientific Evaluation
- [ ] random split が危険な場合
- [ ] scaffold / temporal / cell-line / patient / species split
- [ ] out-of-distribution generalization
- [ ] prospective validation
- [ ] experimental validation
- [ ] data leakage through biological similarity

## Interpretability & Mechanism
- [ ] predictive explanation vs causal mechanism
- [ ] feature attribution の限界
- [ ] biological prior の利用
- [ ] hypothesis generation と hypothesis confirmation を分ける

## Drug Discovery / Precision Medicine
- [ ] target identification
- [ ] molecular property / interaction prediction
- [ ] drug response prediction
- [ ] biomarker discovery
- [ ] combination prediction
- [ ] translational gap: cell line → patient

## Scientific Agents
- [ ] literature retrieval
- [ ] evidence aggregation
- [ ] hypothesis generation
- [ ] experiment planning
- [ ] tool use
- [ ] provenance / citation
- [ ] uncertainty and conflicting evidence

## Must-answer Questions
1. Why are random train/test splits often misleading in biomedical ML?
2. What does OOD generalization mean in biology?
3. When is a GNN preferable to a Transformer, and vice versa?
4. How would you validate that a model learned biology rather than dataset artifacts?
5. What makes scaling biological foundation models different from language models?
6. Predictive accuracy is high—why might the model still be scientifically useless?
7. How should AI-generated scientific hypotheses be evaluated?
