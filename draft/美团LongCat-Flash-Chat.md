Zero-computation Experts: 这个观点和HET 80-20 是一致的

Shortcut-connected MoE (ScMoE): moe结构的东西我不懂啊

训练稳定
- Variance Alignment: 看来不稳定是个经常出现的问题, 方差修正..., 怎么修的, 和muon一样吗,
- Router/Loss 平衡
- 隐藏 z-loss 抑制爆炸激活
- Adam ε 超小化(1e-16)

Hyperparameter Transfer: 这个和我们做的事情是一样的, 就是不知道他们得到的超参是多少呢

Model Growth Initialization: 啥意思, 先冷冻?先freeze? 那先freeze哪一部分呢

多agent 合成框架: 那模型作为大脑需要什么能力呢

他们写了新的框架吗?
- silent data corruption: 这是啥
- Kernel 优化
- 大规模并行

推理与部署, 这个地方看不懂啊, 但感觉很重要:
- SBO 推理调度
- Speculative Decoding + MTP
- KV Cache 优化 & 量化
