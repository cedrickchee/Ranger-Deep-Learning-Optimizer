# [Ranger Neural Network Optimizer](https://forums.fast.ai/t/meet-ranger-radam-lookahead-optimizer/52886?u=cedric)

Ranger — a synergistic optimizer combining RAdam (Rectified Adam) and Lookahead in one codebase.

> - RAdam stabilizes training at the start. (reference: ["On the Variance of the Adaptive Learning Rate and Beyond"](https://arxiv.org/abs/1908.03265v1) paper by Liyuan Liu et al.)
>
> - Lookahead stabilizes training and convergence during the rest of training. (reference: ["Lookahead Optimizer: k steps forward, 1 step back"](https://arxiv.org/abs/1907.08610v1) paper by Michael Zhang, Geoffrey Hinton, et al.)

## Examples

_Usage and notebook to test with comming shortly._

## Software Requirements

- Python 3.x
- PyTorch 1.x

## License

[Apache License 2.0](./LICENSE)

## Credits

Based on original work done by [Less Wright (lessw2020)](https://github.com/lessw2020). He built on LonePatient's implementation for the Lookahead part, and the official RAdam code for RAdam:

- Lookahead implementation from LonePatient - https://github.com/lonePatient/lookahead_pytorch/blob/master/optimizer.py
- RAdam code by https://github.com/LiyuanLucasLiu/RAdam/blob/master/radam.py
