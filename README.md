# [Ranger Deep Learning Optimizer](https://forums.fast.ai/t/meet-ranger-radam-lookahead-optimizer/52886?u=cedric)

Ranger — a synergistic optimizer combining RAdam (Rectified Adam) and Lookahead in one codebase.

> - RAdam stabilizes training at the start. (reference: ["On the Variance of the Adaptive Learning Rate and Beyond"](https://arxiv.org/abs/1908.03265v1) paper by Liyuan Liu et al.)
>
> - Lookahead stabilizes training and convergence during the rest of training. (reference: ["Lookahead Optimizer: k steps forward, 1 step back"](https://arxiv.org/abs/1907.08610v1) paper by Michael Zhang, Geoffrey Hinton, et al.)

(I built on LonePatient's implementation for the Lookahead part, and the official RAdam code for RAdam).

_Usage and notebook to test with comming shortly._

## Software Requirements

- Python 3.x
- PyTorch 1.x

## License

[Apache License 2.0](./LICENSE)
