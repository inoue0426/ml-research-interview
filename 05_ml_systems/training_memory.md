# Training Memory

Status: 🔴
Priority: ★★★★★

## 最低限押さえる
- [ ] parameter memory
- [ ] gradient memory
- [ ] optimizer-state memory
- [ ] activation memory
- [ ] master weights / mixed precision の場合
- [ ] activation checkpointing
- [ ] sequence length / batch size が memory に与える影響

## 日本語で理解

## English Explanation

## Calculation Exercises
- [ ] N parameters × bytes/parameter
- [ ] Adam states を含む概算
- [ ] activation memory の主要依存変数

## Interview Questions
1. Why can optimizer states dominate memory?
2. What does activation checkpointing trade?
3. Why does longer context increase memory sharply?

## Personal Notes / TODO
