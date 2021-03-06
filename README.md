# Social Reinforcement Learning

This repo implements:
- A multi-agent gridworld environment in `gym_multigrid/`
- Multi-agent PPO training code in `multiagent_tfagents/`
- Adversarial environment generation code with PAIRED in `adversarial_env/`

The latter directory implements the code supporting the publication:
>Dennis,  M.\*, Jaques, N.\*,  Vinitsky,  E.,  Bayen,  A.,  Russell,  S.,
>Critch,  A.,  &  Levine,  S., [Emergent Complexity and Zero-Shot Transfer via
>Unsupervised Environment Design](https://bit.ly/2Hitysn), Neural Information 
>Processing Systems (NeurIPS), Virtual (2020).

Please see the README file in each subdirectory for more details.

This is not an official Google product.

## Installation
* requires linux
* create Python 3.10 environment (e.g. with conda)
* $ pip3 install --upgrade pip
* $ pip3 install tensorflow
* $ pip3 install -r requirements.txt

* Run test: $ python3 -m adversarial_env.test_adversarial_env