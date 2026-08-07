# Minimum Knowledge — Reinforcement Learning

目標は RL 教科書を網羅することではなく、**MDP → value → policy gradient → actor-critic → PPO → LLM RL** を連続して説明できること。

## MDP
- [ ] state / action / reward / transition / policy
- [ ] return
- [ ] discount factor
- [ ] Markov property

## Value Functions
- [ ] V(s)
- [ ] Q(s,a)
- [ ] advantage A(s,a)
- [ ] Bellman expectation equation
- [ ] Bellman optimality equation

## Value-based RL
- [ ] dynamic programming
- [ ] Monte Carlo vs temporal difference
- [ ] Q-learning
- [ ] on-policy vs off-policy
- [ ] exploration vs exploitation

## Policy Gradient
- [ ] policy gradient theorem の直感
- [ ] REINFORCE
- [ ] log-derivative trick
- [ ] baseline が variance を下げる理由

## Actor-Critic
- [ ] actor と critic
- [ ] advantage estimation
- [ ] GAE の目的
- [ ] bias-variance tradeoff

## TRPO / PPO
- [ ] なぜ policy update を制約したいか
- [ ] importance ratio
- [ ] PPO clipped objective
- [ ] clipping が何をしているか
- [ ] entropy bonus
- [ ] value loss
- [ ] PPO failure modes

## LLM RL
- [ ] prompt = state/context とみなす考え方
- [ ] token sequence = action trajectory
- [ ] reward model / verifiable reward
- [ ] KL penalty / reference policy
- [ ] credit assignment
- [ ] sparse rewards
- [ ] reward hacking
- [ ] online vs offline preference optimization

## Must Derive / Explain
- [ ] Bellman equation
- [ ] REINFORCE estimator
- [ ] baseline が expectation を変えないこと
- [ ] PPO clipped objective の各項

## Must-answer Questions
1. Value-based vs policy-based RL?
2. On-policy vs off-policy?
3. Why does REINFORCE have high variance?
4. Why use a critic?
5. What problem is PPO trying to solve?
6. Why can PPO clipping stabilize training?
7. How is RL for an LLM different from standard control RL?
8. How can reward hacking appear in post-training?
