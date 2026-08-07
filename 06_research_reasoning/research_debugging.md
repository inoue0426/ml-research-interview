# Research Debugging

Status: 🔴
Priority: ★★★★☆

## 最低限押さえる
悪い結果を以下に分解する。
- [ ] data issue
- [ ] optimization issue
- [ ] architecture issue
- [ ] objective mismatch
- [ ] implementation bug
- [ ] evaluation issue
- [ ] insufficient compute / training

## 日本語で理解

## English Explanation

## Drills
1. Training loss は下がるが validation は悪化する。
2. 7B→70B で改善しない。
3. 新しい module を入れると seed variance が増える。
4. Offline metric は改善するが real task performance は悪化する。

## Interview Questions
1. How do you prioritize debugging hypotheses?
2. What is the cheapest discriminating experiment?
3. How do you distinguish optimization from model-capacity problems?

## Personal Notes / TODO
