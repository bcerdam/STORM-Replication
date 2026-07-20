# PyTorch replication of STORM: Efficient Stochastic Transformer based World Models for Reinforcement Learning.

This repo contains my implementation of the sample-efficient world model called STORM, built entirely from scratch.

## Setup

**1. Clone the repo**

```bash
git clone https://github.com/bcerdam/STORM-Replication.git
cd STORM-Replication
```

**2. Create a virtual environment**

```bash
python -m venv venv
```

**3. Activate the virtual environment**

```bash
source venv/bin/activate
```

**4. Install the requirements**

```bash
pip install -r requirements.txt
```

## Configuration

If necessary, you can go to config/ to change the agent, world model or environment parameters.

## Training

```bash
python3 train.py
```

## Evaluation

...

## Acknowledgments

If this repo was useful to you, I ask that you please cite the original authors and give this repo a star. If you have any questions about the paper or the code implementation, open an issue and I will gladly answer them.

```bibtex
@inproceedings{
    zhang2023storm,
    title={{STORM}: Efficient Stochastic Transformer based World Models for Reinforcement Learning},
    author={Weipu Zhang and Gang Wang and Jian Sun and Yetian Yuan and Gao Huang},
    booktitle={Thirty-seventh Conference on Neural Information Processing Systems},
    year={2023},
    url={https://openreview.net/forum?id=WxnrX42rnS}
}
```
